# Readings: Authentication & Production Server

# JSON Web Tokens
JSON Web Token `(JWT)` is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 

**When should you use JSON Web Tokens?**

- **Authorization :** This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token.

- **Information Exchange :** JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are.


**JSON Web Token structure**

- Header 
- Payload
- Signature

#  DRF JWT Authentication
**How to install it?**

`pip install djangorestframework_simplejwt`

then in the settings.py :

```python
REST_FRAMEWORK = {
    'DEFAULT_AUTHENTICATION_CLASSES': [
        'rest_framework_simplejwt.authentication.JWTAuthentication',
    ],
}
```
then in the urls.py :

```python
from django.urls import path
from rest_framework_simplejwt import views as jwt_views

urlpatterns = [
    # Your URLs...
    path('api/token/', jwt_views.TokenObtainPairView.as_view(), name='token_obtain_pair'),
    path('api/token/refresh/', jwt_views.TokenRefreshView.as_view(), name='token_refresh'),
]
```

## Django Runserver Is Not Your Production Server

**A Production Stack**

A production setup usually consists of multiple components, each designed and built to be really good at one specific thing. They are fast, reliable and very focused.

When a request arrives at your server, it should be passed to a dedicated web server

**How Does Django Fit In?**
in Django app does not actually run as you would think a server would - waiting for requests and reacting to them. Your project provides a uwsgi.py file, which contains a function to be called by the application server. This function gets a Python object representing the incoming request.
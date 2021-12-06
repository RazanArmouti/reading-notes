# Readings: Django CRUD and Forms
## ***Django Forms*** 
 An HTML Form is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server. Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data, including text boxes, checkboxes, radio buttons, date pickers and so on. Forms are also a relatively secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.

 jango's form handling uses all of the same techniques that we learned about in previous tutorials (for displaying information about our models): the view gets a request, performs any actions required including reading data from the models, then generates and returns an HTML page (from a template, into which we pass a context containing the data to be displayed). What makes things more complicated is that the server also needs to be able to process data provided by the user, and redisplay the page if there are any errors.
 ![django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms/form_handling_-_standard.png)

 Creating and handling forms can be a complicated process! Django makes it much easier by providing programmatic mechanisms to declare, render, and validate forms. Furthermore, Django provides generic form editing views that can do almost all the work to define pages that can create, edit, and delete records associated with a single model instance.

## ***Django Templates***
 The following diagram describes the main data flow, and the components required when handling HTTP requests and responses. As we already implemented the model, the main components we'll create are:

 1. URL mappers to forward the supported URLs (and any information encoded in the URLs) to the appropriate view functions.
 2. View functions to get the requested data from the models, create HTML pages that display the data, and return the pages to the user to view in the browser.
 3. Templates to use when rendering data in the views. 
 ![django-url](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page/basic-django.png)

## ***Django Views*** 




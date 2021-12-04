# Readings: Intro to Django

## ***Getting started with Django*** 
 Install Django¶
 You’ve got three options to install Django:

 1. Install an official release. This is the best approach for most users.
 2. Install a version of Django provided by your operating system distribution.
 3. Install the latest development version. This option is for enthusiasts who want the latest-and-greatest features and aren’t afraid of running brand new code. You might encounter new bugs in the development version, but reporting them helps the development of Django. Also, releases of third-party packages are less likely to be compatible with the development version than with the latest stable release.

## ***How Django Works Behind the Scenes***
 Django is a Python-based web framework used by millions of developers and billions of consumers through popular apps like Instagram. It is open source, meaning the code is available for free on Github and can be downloaded onto any developer’s computer and used alongside the official documentation.

## ***What is Django*** 
 Django is a high-level Python web framework that enables rapid development of secure and maintainable websites. Built by experienced developers, Django takes care of much of the hassle of web development, so you can focus on writing your app without needing to reinvent the wheel. It is free and open source, has a thriving and active community, great documentation, and many options for free and paid-for support.
 Django helps you write software that is:
 1. Complete
 2. Versatile
 3. Secure
 4. Scalable
 5. Maintainable
 6. Portable

 Django is now a thriving, collaborative open source project, with many thousands of users and contributors. While it does still have some features that reflect its origin, Django has evolved into a versatile framework that is capable of developing any type of website.

 ![Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction/basic-django.png)

 The preceding sections show the main features that you'll use in almost every web application: URL mapping, views, models and templates. Just a few of the other things provided by Django include:

 1. Forms: HTML Forms are used to collect user data for processing on the server. Django simplifies form creation, validation, and processing.
 2. User authentication and permissions: Django includes a robust user authentication and permission system that has been built with security in mind.
 3. Caching: Creating content dynamically is much more computationally intensive (and slow) than serving static content. Django provides flexible caching so that you can store all or part of a rendered page so that it doesn't get re-rendered except when necessary.
 4. Administration site: The Django administration site is included by default when you create an app using the basic skeleton. It makes it trivially easy to provide an admin page for site administrators to create, edit, and view any data models in your site.
 5. Serialising data: Django makes it easy to serialise and serve your data as XML or JSON. This can be useful when creating a web service (a website that purely serves data to be consumed by other applications or sites, and doesn't display anything itself), or when creating a website in which the client-side code handles all the rendering of data.

## ***First Django App - Part 1*** 
 The path() function is passed four arguments, two required: route and view, and two optional: kwargs, and name. At this point, it’s worth reviewing what these arguments are for.

## ***First Django App - Part 2*** 

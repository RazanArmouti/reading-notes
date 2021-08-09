# Read: 13 - Local Storage

## ***THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS***
 *They have three potentially dealbreaking downsides:*

  1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
  2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
  3. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## ***A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5***
 1. userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available.
 2. Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects.
 3. Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers. 

 ## ***INTRODUCING HTML5 STORAGE***
  It’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. 

 ## ***USING HTML5 STORAGE***
  HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 

 ## ***TRACKING CHANGES TO THE HTML5 STORAGE AREA*** 
  The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.

## ***LIMITATIONS IN CURRENT BROWSERS*** 

## ***HTML5 STORAGE IN ACTION*** 
 with HTML5 Storage, we can save the progress locally, within the browser itself. 

## ***BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS*** 
 A new API has been standardized and implemented across all major browsers, platforms, and devices. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database.



 
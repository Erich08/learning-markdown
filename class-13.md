# Local Storage

> Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

According to this article, cookies were invented early on in browser history, but they have three disadvantages:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## HTML5 Storage
HTML5 storage allows you to store data in key/value pairs locally within the clients web browser. This way, the data will persist of the user navigates away from the page and or closers the browser tab.
This data is never transmitted to a to server which is clear advantage over cookies.

Which browsers support HTML5 storage? I have provided a list below:

1. IE 8.0+
2. Firefox 3.5+
3. Safari 4.0+
4. Chrome 4.0+
5. Opera 10.5+
6. Iphone 2.0+
7. Android 2.0+

> HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
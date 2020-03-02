## Local Storage:
LocalStorage is a type of web storage that allows Javascript websites and apps to store and access data right in the browser with no expiration date. This means the data stored in the browser will persist even after the browser window has been closed.

## HTML5 STORAGE:
**HTML5 Storage** is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.
it’s a way for web pages to store named key/value pairs locally, within the client web browser. this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you  

APPLICATIONS HTML5 STORAGE SUPPORT:
|           |           |           |           |           |           |           |
| --------- | --------- | --------- | --------- | --------- | --------- | ---------:|
|IE         |	FIREFOX |	SAFARI  |	CHROME  |	OPERA   |	IPHONE  |	ANDROID |
|8.0+       |	3.5+	|   4.0+    |	4.0+    |   10.5+   |	2.0+    |	2.0+    |

From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object

### USING HTML5 STORAGE
HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats

### How to Use LocalStorage in JavaScript??:
There are five methods to use localStorage in your web applications:
1. ``setItem()``: Add key and value to localStorage
2. ``getItem()``: Retrieve a value by the key from localStorage
3. ``removeItem()``: Remove an item by key from localStorage
4. ``clear()``: Clear all localStorage
5. ``key()``: Passed a number to retrieve nth key of a localStorage

### LocalStorage JavaScript limitations:

As easy as it is to use localStorage, it is also easy to misuse it. The following are limitations and also ways to NOT use localStorage:
- Do not store sensitive user information in localStorage
- It is not a substitute for a server based database as information is only stored on the browser
- LocalStorage is limited to 5MB across all major browsers
- LocalStorage is quite insecure as it has no form of data protection and can be accessed by any code on your web page
- LocalStorage is synchronous. Meaning each operation called would only execute one after the other
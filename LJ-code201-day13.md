#LJ Code 201 - Day 13

#Local Storage

Cookies used to be the main way to store info in the browser, but some of it's weaknesses are:
- can't hold a lot of data
- sends to the server ach time you request a page from the domain
- not very secure

Enter HTML5 and localStorage:
- stores data when you close a window or tab
- all open windows and tabs have access to the data
- the data is stored as properties of the storage objects, using in key/value pairs, and the value in the pair is always a string

How to access the storage API:
- to save an item into the storage object, you us the setItem() method, which takes two parameters (the name of the key and the associative value)
- to retrieve a value from the storage object you use the getItem() method, passing it the key
- the storage objects often store JSON-formatted data (the parse() method is used to turn the JSON-formatted data into a JS object, and the stringify() method is used to transform objects into JSON-formatted strings)

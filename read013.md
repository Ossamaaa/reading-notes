HTML5 Storage is based on named key/value pairs. 
You store data based on a named key, then you can retrieve thatdata with the same key.
 The named key is a string. 
 The data can be any type supported by JavaScript, including
strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and
retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce
your retrieved data into the expected JavaScript datatype.

If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage
event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will
not fire, because nothing actually changed in the storage area.

One vision is an acronym that you probably know already: SQL. In 2007, Google launched Gears, an open source cross-browser plugin
which included an embedded database based on SQLite. This early prototype later influenced the creation of the Web SQL Database
specification. Web SQL Database (formerly known as “WebDB”) provides a thin wrapper around a SQL database, allowing you to do things
like this from JavaScrip
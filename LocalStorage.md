# Local Storage  
---  
Local storage before HTML5 was not nearly as efficiant as it is now. Cookies were invented early in the web's history, but are incredibly inefficiant.  

In the past only internet explorer was really used as the internets main browser. In order to keep there browser on top, they invented what is called **DHTML Behaviors**, and one of thes behaviors was called userData. userData allows web pages to store up to 64 KB of data per domain. 

In 2002 adobe introduced a feature in Flash, properly known as ** Local Shared Objects**, it alloweds Flash objects to store up to 100 KB of data per domain.  

In 2007 Google launched Gears, an open sourced browser plugin. After obtaining permission from the user, Gears can store unlimited amounts of data per domain in SQL database tables.  

All of these solutions are either browser specific or reliant on a third party plugin. Thats where HTML5 comes in.  

# HTML5  

HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser. Unlike all previous attempts it is implemented natively in the web browser.  

HTML5 storage is based on named key/value pairs. You store data based on a named key, then you can retrieve said data witht the same key. Data is always stored as a string so to retrieve anything else you will need to use functios such as *parseInt()* or *parseFloat()*.  

- setItem() will place said value into storage.  
- getItem() will show you said value.  
- removeItem() is pretty self explanitory.  
- clear() will clear all stored values  
- key() is a way to get the total number of values in the storage area and to iterate through all of the *keys* like indexes.  


Although HTML5's condition is great compared to the past, there are still others with different visions competing. SQL and the Indexed Database API are two of those competing visons. We will see where the future takes us.  


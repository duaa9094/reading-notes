# Read: 13 - Local Storage
## What is HTML Web Storage?

With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

HTML web storage provides two objects for storing data on the client:
-	`window.localStorage` stores data with no expiration date
-	`window.sessionStorage` stores data for one session (data is lost when the browser tab is closed)


 **setItem()** method of the Storage interface, when passed a key name and value, will add that key to the given Storage object, or update that key's value if it already exists.
 
 **getItem()** method of the Storage interface, when passed a key name, will return that key's value, or null if the key does not exist, in the given Storage object.

 **removeItem()** method of the Storage interface, when passed a key name, will remove that key from the given Storage object if it exists.


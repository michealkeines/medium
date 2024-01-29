

HTTP/2 is much faster and more efficient than HTTP/1.1. One of the ways in which HTTP/2 faster is in how it prioritizes content during the loading process.

Prioritization affects a webpage's load time. for example, certain resources, like large javascript files, may block the rest of the page from loading if they have to load first. 

Multiplexing: HTTP/1.1 loads resources one after the other, so if one resource cannot be loaded, it blocks all the other resources behind it. in contrast, HTTP/2 is able to use a single TCP connection to send multiple streams of data at once so that no one resource blocks the other resource.

Server PUSH: a server only sends content to a client if the client asks for it. the server also sends a message letting the client know what pushed content to expect

Header compression: HTTP/2 uses more advanced compression method called HPACK that eliminates redundant information in HTTP header packets


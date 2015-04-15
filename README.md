node-static-http-server
=======================

A simple, nodeJS, http development server that trivializes serving static files. 

This server is HEAVILY based on work done by Ryan Florence(https://github.com/rpflorence) (https://gist.github.com/701407). I merged this code with suggestions on handling varied MIME types found at Stackoverflow (http://stackoverflow.com/questions/7268033/basic-static-file-server-in-nodejs).

To run the server simply place the server.js file in the root of your web application and issue the command:

$ node server.js

or

$ node server.js 1234

with "1234" being a custom port number"

Your web application will be served at http://localhost:8888 by default or http://localhost:1234 with "1234" being the custom port you passed.

Mime Types:
You can add to the mimeTypes has to serve more file types.

Virtual Directories:
Add to the virtualDirectories hash if you have resources that are not children of the root directory

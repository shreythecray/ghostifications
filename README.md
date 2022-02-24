# Mastering APIs Challenge

Goal: Build a project that demonstrates your ability to make GET and POST requests with any two APIs.

# Sample Project:

In index.js you will find "Ghostifications Mood Moniro", a simple Node.js project that uses the following APIs to get your mood as user input and send an email with 

### Setting Up

1. Create a Node.js app
    Create an empty file called `app.js` and add the following code to it:
    
    ```javascript
    const http = require('http');

    const hostname = '127.0.0.1';
    const port = 3000;

    const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Hello World');
    });

    server.listen(port, hostname, () => {
    console.log(`Server running at http://${hostname}:${port}/`);
    });
    ```

    [📝 Learn more about using Node.js](https://nodejs.org/en/docs/guides/getting-started-guide/).

2. Run your web server using the command `node app.js` and visit `http://localhost:3000` to view it.

### Making Your First GET Request
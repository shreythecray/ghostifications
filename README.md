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

    [📝 Learn more about using Node.js](https://nodejs.org/en/docs/guides/getting-started-guide/)

2. Run your web server using the command `node app.js`

    You will get a response in the form of `Server running at <url>`

3. Visit `http://localhost:3000` or the `<url>` from the command's response to view it
    
    The server will display "Hello World!", which you will recognize is from your app.js on line 9: `res.end('Hello World');`. Try changing the argument of `res.end()` to and re-run the `node app.js` command to see how you can manipulate your new app.

    [📝 Learn more what's happening in the code](https://nodejs.dev/learn/introduction-to-nodejs)

### Making Your First GET Request
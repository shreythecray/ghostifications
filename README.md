# Mastering APIs Challenge

Goal: Build a project that demonstrates your ability to make GET and POST requests with any two APIs.

### 🏆 Show Off Your Project

Completed the challenge? Share your project submission here.
1. Fork this repository
2. Edit the `readme.md` file
3. Add the link to your project's GitHub repo below the "Projects" heading (copy the example)
5. Commit your changes
6. Create a PR (pull request) to the `main` branch of my repo

Note:
* Make sure your repo is public
* Explain what your project does and how it works in your project `readme.md` file
* Hide your pirvate API keys
* [📝 Learn more hiding API keys](https://dev.to/ptprashanttripathi/how-to-hide-api-key-in-github-repo-2ik9)

# Projects

* Example_Project_Name: https://link_to_project

# Sample Project:

👻 Boo, the ghost, can only communicate with the real world through API requests. A very peculiar situation, but I don't make the rules. The most effective way to communicate with APIs is through notifications: 📧 emails, 💬 text messages, 📲 push notifications, 📳 direct messages, take your pick.

In index.js you will find "Ghostifications: Messages from the Afterlife", a simple Node.js project that allows 👻 Boo, the ghost, to communicate with the real world from the afterlife through 📞 notifications.

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

### GET Request: get your 

### POST Request: send notifications with Courier
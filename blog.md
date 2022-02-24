# [Workshop] Intro to APIs with Node.js

## Introduction

Hi, I'm Shreya 👋 when I first started college, I sucked at coding and was convinced that I would never make it in tech. I was so intimidated by coding that I lost all interest in my classes and started focusing on side projects to teach myself the basics. In April 2019, I co-founded [Bit Project](https://bitproject.org/) (a 501(c)(3) nonprofit organization) as an educational playground where students who build their own projects and help teach other how to code outside of the traditional classroom. Bit Project is now a global student community of over 1200 students all co-learning and teaching programming skills.

I never did end up becoming a software engineer, but I did graduate from UC Davis with a BS in Computer Science and Engineering in June 2021 and found a place in tech where I could use my experience as a developer and interest in education to work in DevRel. Now, I work as a Developer Advocate at Courier, a startup building a product notifications API (more on that in a moment).

This workshop is a hands-on Introduction to APIs workshop meant to help you develop a fundamental understanding of APIs and feel comfortable integrating them into your own projects.

### Why should you care about APIs?

Building a successful project, whether it is for hackathons or classes, requires three main characteristics:
1. High performance: your project needs to work, and specifically in the way that you intended it to
2. Sustainability: your project needs to survive past the deadline, whether it's to show it off to judges, professors, or friends
3. Speed: there's always a deadline, and you need to deliver your project in time

Building a successful **software product**, requires these same characteristics, but with additional urgency:
1. Higher stakes for high performance: your project needs to perform well, not just for your or your judges, but for your users and stakeholders 💰
2. More resources for sustainability: to build a sustainable, you need more time, more money, more people, more of everything
3. Greature pressure to deliver at a high speed: your users need your product and vice versa as quickly as possible, so that you can start making money as quickly as possible, to get the resources you need to keep building and make a high performing, sustainable product

APIs are an example of many solutions exist to help you deliver a project/product that can satisfy these characteristics.

### Meet Boo!

Ghostifications is a project I built at Courier to demonstrate how easy it is to integrate notifications into various applications.

> 👻 Boo, the ghost, can only communicate with the real world through API requests. A very peculiar situation, but I don't make the rules. The most effective way to communicate with APIs is through notifications: 📧 emails, 💬 text messages, 📲 push notifications, 📳 direct messages, take your pick.

For this workshop, we will first learn the fundamentals of working with APIs and making GET and POST requests. We will then take these skills to build "Ghostifications: Messages from the Afterlife", a simple Node.js project that allows 👻 Boo, the ghost, to communicate with the real world from the afterlife through 📞 notifications.

## So, what is an API?

API = Application Programming Interface. Let's break it down:
* Application: for software programs
* Programming: used for coding (in this case communicating via code)
* Interface: a point where two systems can interact

API = an interface that helps software programs interact/communicate by accessing and sharing each other's data.

It's okay if the definition doesn't make sense yet, but I would really encourage you to revisit it after completing the coding challenges below. You can then make connections between the definitation of APIs and what happened when you saw them in action.

APIs help your product satisfy those characteristics we spoke about earlier by:
1. providing reliable and tested solutions
2. minimizing the code, effort, and other resources you would need if you were to build the same solution from scratch
3. delivering code quickly

### API architecture

APIs make calls between the application and a server. The server holds a bunch of data that your application / you want access to.

How can you interact with the data in the server that your application wants access to? **HTTP requests** AKA “HTTP verbs” - indicate the type of action a specific API call can do. Some examples of these requests are: GET, POST, PUT, DELETE.
* GET request: retrieve data
* POST request: send data, affecting change on the server
* PUT request: replace specified resource with request payload
* DELETE request: deletes specified resources

An HTTP request is made from a client (your app) to the server via a url, which allows the client to locate the server. When you try to access a website on your browser, you use the url to make an HTTP request to the website's server. When you try to access `github.com`, you are using the url to make an HTTP request to GitHub's server to access the contents of that website.

**REST APIs** (Representational State Transfer)

REST is a software architectural style that is applied to web APIs. It provides a simple, uniform interface for APIs, which makes it the most commonly used API architectural style. One of the requirements for an API to be considered a REST API is that it needs to manage requests through HTTP.

**Building an HTTP Request**

The following are the components required to make an API call via an HTTP request:
1. A URL that specifies the “endpoint” you are making the request to
   `https://cataas.com/cat`
2. Parameter(s) that provide “options” that influence the response
   Endpoint: `https://cataas.com/cat`
   With one parameter called color: `https://cataas.com/cat?color=blue`. You need to separate the endpoint from the parameter(s) with a `?`
   With a second parameter called tag: `https://cataas.com/cat?color=blue&tag=angry`. Notice that you need to separate multiple parameters with a `&`.
3. The type of request (GET? POST? etc.)

Try searching the endpoints above in your browser and seeing what happens.

[📝 Learn more about the CATAAS API](https://cataas.com/#/)

### 🛠 Activity: Popular APIs

Twitter API
* GET request: “get” tweets or data about tweets
* POST request: create, delete, retweet tweets
* [📝 Learn more about the Twitter API](https://developer.twitter.com/en/docs/twitter-api)

Spotify API
* What do you think Spotify's GET request does?
* What do you think Spotify's POST request does?
* [📝 Learn more about the Spotify API](https://developer.spotify.com/documentation/web-api/)

Twilio API
* What do you think Twilio's GET request does?
* What do you think Twilio's POST request does?
* [📝 Learn more about the Twilio API](https://www.twilio.com/docs/usage/api)

### 🛠 Activity: API Use Cases

Take a moment now to think about other use cases for APIs. What type of data would you need access to where having an API might be helpful.

[📝 A collective list of APIs.](https://apilist.fun/)

### Testing APIs

### Product notifications with Courier

## Challenges

# Final project

[Learn more about the final project](https://github.com/shreythecray/ghostifications#mastering-apis-challenge)
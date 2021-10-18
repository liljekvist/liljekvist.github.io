---
title: Privacy focused forum
author: Mikael Bohlin Liljekvist
date: 2021-08-1 00:00:00 +2000
categories: [C++, drogon, Project]
tags: [WIP]
---

I'm working on a concept website together with a friend. It has a backend written in C++ and a frontend using HTML, CSS and JavaScript. We have divided the work into frontend and backend. Im doing the backend part. The vision is that it's a forum that is focused on privacy. There is no register- or login-system, instead its using cookies to identify a user. We don't save any information about the user other than a random string we call Unique User Identifier (UUID) and a random int User Identifier (UID). The cookie we send to the user is the UUID and is the translated into the UID, the UID is then viewed almost as a username on the website. To write the backend I am using a framework called [Drogon](https://github.com/drogonframework/drogon).

## Links

* [Github Repository](https://github.com/liljekvist/website)
* [Drogon](https://github.com/drogonframework/drogon)

## Contributors

* [Christoffer Ljung Ahlstedt](https://github.com/ChristofferLjungAhlstedt)
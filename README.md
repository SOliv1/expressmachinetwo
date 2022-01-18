[![pages-build-deployment](https://github.com/SOliv1/expressmachinetwo/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/SOliv1/expressmachinetwo/actions/workflows/pages/pages-build-deployment)

# expressmachinetwo


We have created a readable and clean code base using Express.Router(). Writing clean and readable code is one of the most important skills as a developer. This will make adding new features much easier as your APIs expand!
Here we clean up our code and separate our application into a file to handle all /expressions routes, and another to handle all /animals routes.
Our machine is fully functional! Our app.js file, however, is getting quite long and hard to read. It’s easy to imagine that as we add functionality to an application, this file would get long and cumbersome.
Luckily, Express provides functionality to alleviate this problem: Routers. Routers are mini versions of Express applications — they provide functionality for handling route matching, requests, and sending responses, but they do not start a separate server or listen on their own ports. Routers use all the .get(), .put(), .post(), and .delete() routes that you know and love.

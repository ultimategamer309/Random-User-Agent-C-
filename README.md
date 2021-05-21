# Raw Traffic


## What It Does
Raw Traffic is a app designed load a page as many times as possible as fast as possible, all routed through your personal proxies. This allows for you to eassily bot traffic to many websites. As of now it only supports loading pages once, however, in the soon future it should also work to bot media streams to any website. This only possible, however, if you buy or rent enough proxies.

## How It Does It
Raw Traffic aims to get the most possible traffic to a website in the least amount of time, while also not beeing too reasource heavy. To do this it is coded purly in c++17 and sends traffic to the target websites with libcurl. Raw Traffic also implements multi-threading with a user deffined number of threads. That way you can use however much or little of your computers resources to complete a task as you want.

## How To Use It
1) copy paste "userAgent.cpp" and userAgent.h" into your projects folder
2) add the files to the project (if your ide makes you)
3) run code

```
//creates new object
userAgent agent;
//every time this is ran it will randomly generate a new agent
agent.getAgent();
```

## Coming Soon
 - filters

---
title: Serverless Everywhere
date: 2019-09-11 17:12:00 +07:00
tags:
- daily
feature-images: "/uploads/server.jpg"
layout: post
---

In the past, if we builded website and connected to API. There were too many things to do, such as developing website/API, setup and maintenance a server and security management.

But now, we are in the digital transformation period. We can only focus on development software and let cloud providers manage the server for us. That's what we call “Serverless”.

> “The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.” ― Albert Einstein

Today, my boss asked me for a help. He had to build a website for voting and viewed the report. First, I chose Svelt framework to build the static website because its new thing which I had to learn. 

Second, I head to the AWS console and created Amazon Api Gateway. This service helped bridge the website and other AWS services. 

Third, I created Amazon Kinesis Data Firehose to receive data from the Amazon API Gateway and push into data storage.

Finally, Hosted website by placed static website to Amazon S3. After the website go online, my boss can view the report via Amazon Athena.
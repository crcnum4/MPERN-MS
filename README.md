# A Simple Blog Microservice

## Synopsis

<p>The following project is a MPERN Microservice Architecture design concept. I created a simple Blog application where posts to videos (uploaded to youtube) can be loaded to the application. Other users will be able to comment and rate the post. future goal is to allow users to chat and trigger a blog to be played while all the users watch the same video allowing for viewing parties.</p>

## Design Architecture Concept

![design-concept][https://drive.google.com/open?id=1tohekhel9xwvudioanfem8249q8iet2t]

## construct

<p>the system is deviced into multiple servers with and seperate databases user only interacts directly with either the gateway or the socket.io server which then requests are sent to the required services which can then interact with other services if additional information is needed.</p>

## links

<p>below are the links to each microservice.</p>

<p>[Gateway](https://github.com/crcnum4/MPERN-Gateway)</p>
<p>[Auth](https://github.com/crcnum4/MPERN-Auth)</p>

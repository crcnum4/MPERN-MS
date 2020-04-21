# A Simple Blog Microservice

## Synopsis

<p>The following project is a MPERN Microservice Architecture design concept. I created a simple Blog application where posts to videos (uploaded to youtube) can be loaded to the application. Other users will be able to comment and rate the post. future goal is to allow users to chat and trigger a blog to be played while all the users watch the same video allowing for viewing parties.</p>

## Design Architecture Concept

![design-concept](https://lh3.googleusercontent.com/ysp2CdTKnTqq0mxOrm9RpXuVQFhRg5H9lSkIwveMtsbcS-evSBe4lPkkCLpvAGfQ4HwECYZLvN24ZMYekFY7cI2KQT2Pr3qQSiVMyczQwQ_FXxtbiXXl-TUYIwp2Mx2_IbzcOqSxnGVHTVXOKfkgeg92qCe7FaBhC_eSvDLNuZh5IksdNinzQBPaCqOrJ8w1V4CNUP3LD9PkDsN5q_HWU25KVW6cwH8S_jOdiJpO_VF0DB57Vixqs3dXdVH0chgjbEML4qRjEiMUAlxWgKeV2TrwNyWNHaS4oSZlHbHqCjujgALSLT43xcr6xhe5LFQDexhmADVEfdxEWzcrbtzQu-S_SM2re8lGhFfzJysufcTQ4sdLid8XBUGyK-Cxwi3qwma7a-N-7mNVS0L85CC6nF_wOs4GDN5KQ46aJ_-KAJL5Jsb_VPH1hNucYDuPwHH70-ZWhXMeBaKzxHhLMqV6pcnl-rH8vSuBKLnCj56o2R6TG1_YOXOcrnQsEdt17q31XZw2qzbSm5IfQiYWnAM5dRSXx0wzRPWD5HiMfaOsQU1uGwinklp8jjyKd7-F11bt1JHKuVzJwif_AdIiCS3N4Hl7NRoKgNo6jYn2BpOUF4cKovHdxHfndzSbS3R0RyyXdzcBZrxku55dxrtW8uz_BZkOdzDJf9b4MgqU-0I6T87yK45SLfRWZR7eQUmQeQ=w962-h882-no "design")

## Construction

<p>the system is deviced into multiple servers with and seperate databases user only interacts directly with either the gateway or the socket.io server which then requests are sent to the required services which can then interact with other services if additional information is needed.</p>

## MPERN

<p>I am using an MPERN stack as a proof of concept that a Javascript focused stack can be used to develop a microservice architecture. The tools used to be clear are:</p>
<p>* M - Mongo (mongoose for db communication) <br />
* P - Postgresql (pg for db communication)<br />
* E - Express.js for routing<br />
* R - React Front End<br />
* N - Node Server</p>
<p>Note: I have considered calling this a MPERNS stack due to the planned addition of a chat microservice using Socket.io for real-time chatting.</p>

## links

<p>below are the links to each microservice.</p>

<p>[Gateway](https://github.com/crcnum4/MPERN-Gateway)</p>
<p>[Auth](https://github.com/crcnum4/MPERN-Auth)</p>

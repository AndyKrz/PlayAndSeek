# PlayAndSeek Application Spring Boot version 

PlayAndSeek - website which is a social network for people interested in different kind of sports. 
You can create a profile which allows you to connect to whole community. You can invite friends and annonce a game. You can chat with whoever you want and arrange a time together. 
Application is based in Java programming language. I used Spring Boot as a base of the project, adding proper security and configuration. For a database I used a H2 framework, where I used already made SQL statements. For layout on internet browser I used basic HTML with Bootstrap and Thymeleaf to extend fresh style of web page. 


## Stack of technologies

**Spring:** SpringBoot, MVC, Data, Security

**Web:** AngularJS, Bootstrap, Bower, Gulp

**Tests:** JUnit, Mockito, AssertJ

## Functionality

- Sign-In / Sign-Up
- Send messages
- Add / remove friends
- Update contact information / Change password
- View person & friend lists
- View person's contact information
- View last messages
- Profile images
- Search

## How to Build & Run application from Intellij

```
git clone https://github.com/AndyKrz/play-and-seek-spring.git
cd play-and-seek-spring
./mvnw clean install
```
Start Spring boot application from the main class: `eu.andykrzemien.playAndSeek.PlayAndSeekApplication;`

Open [http://localhost:8080](http://localhost:8080) in your browser

The links below to get an application ids and secrets:

- Google: [https://developers.google.com/+/web/signin/server-side-flow#step_1_create_a_client_id_and_client_secret](https://developers.google.com/+/web/signin/server-side-flow#step_1_create_a_client_id_and_client_secret)
- Facebook: [https://developers.facebook.com/docs/facebook-login/v2.2](https://developers.facebook.com/docs/facebook-login/v2.2)

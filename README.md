# PlayAndSeek Application Spring Boot version 
Web App helping people to find a partners to play

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


# oauth2-demo
Oauth2 Authentication with Google provider in Spring Boot

# How to config
- Clone project into your computer.
- Put your *Google Oauth2 ID Client* credentials (you can get it in https://console.developers.google.com/apis/credentials) in **application.properties**.
- Run ***gradlew bootRun*** (Windows) or ***./gradlew bootRun*** (UNIX) in project's directory.

# How it works
There are **2 endpoints** for testing: one for **all users** (http://localhost:8080) and other for **authenticated users** (http://localhost:8080/restrited). The second one redirects to Google Login for authentication.

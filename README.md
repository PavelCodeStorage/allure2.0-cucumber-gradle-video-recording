AllureCucumberGradle
---
Overview:
---
Repository provide configuration example of Allure2.0 with Gradle

---
NOTE:
To receive report need to make configution: https://docs.qameta.io/allure/#_reporting

1. Execute **docker-compose up**
2. Download vnc image: **docker pull selenoid/vnc:chrome_65.0**
3. Download image for video recording **docker pull selenoid/video-recorder:latest-release**
4. Execute **gradlew clean test**
5. To perform report generation use **allure serve ./build/allure-results/**

See results: 

![video](https://user-images.githubusercontent.com/26840848/61888594-7477fe00-af0c-11e9-843e-06fd611a0d0c.gif)

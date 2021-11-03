# WEB ENGINEERING - NOVEMBER 2021 
## PRIMARY GOAL- LAB2

### Deployment
To deploy client and server as well, I use the following commands:

./gradlew :server:check --> checking

./gradlew :server:build --> compile and build server file 

./gradlew :server:bootRun --> run server

The same for the client just change "serve" for "client"

### Solution server

To fix the server I complete the code of the function *translation()*:
```
 fun translation(@RequestPayload request: TranslationRequest): TranslationResponse = 
                    TranslationResponse().apply{ translation = "¡Tradúceme!"}
```

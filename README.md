## OAuth Social Login with GitHub using Spring Boot
This is a sample Spring Boot application that demonstrates how to implement OAuth Social Login with GitHub.

### Getting Started
#### Prerequisites
- Java 8 or higher
- GitHub account
- GitHub OAuth application credentials (Client ID and Client Secret)

#### Running the application
1. Clone this repository using git clone `https://github.com/telman03/social-login-oauth`
2. Navigate to the project directory using `cd social-login-oauth`
3. Open `src/main/resources/application.properties` file and replace `YOUR_CLIENT_ID` and `YOUR_CLIENT_SECRET` with the actual values of your GitHub OAuth application credentials.
4. Run the application using `mvn spring-boot:run`
5. Open a web browser and navigate to `http://localhost:8080/secured`. You should be redirected to the GitHub login page.
6. Enter your GitHub credentials and authorize the application to access your GitHub account.
7. You should be redirected back to the application with your GitHub profile information displayed on the page.

#### Reference
[Spring OAuth Documentations](https://docs.spring.io/spring-security/reference/servlet/oauth2/index.html)

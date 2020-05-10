

# oAuthGithub

There are many projects that demonstrates  how to integrate Spring Boot with Github. This project focusses on under the hood what is happening

# Needs

1. The application needs an Authentication Mechanism provided by external vendor.
2. The Application does not want to keep up the usernames and passwords.
3. The Application can keep up the application specific user data in its own database .

#Poc

1. Github is used as a proof of concept to give the Autentication. (Github plays Authentication Provider Role)


Architecture :

There are three components involved

1. Browser
2. The Application (oAuthGithub ) which is the Service Provider
3. Github the Authentication Provider


![Screenshot](GitHubOAuth.jpg)

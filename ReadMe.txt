# OAuth demo based on Spring.io
(https://spring.io/guides/tutorials/spring-boot-oauth2/#_social_login_simple)

## Instructions
1. Single Sign on with Facebook 
(End result: run the main method, going to localhost:8080 automatically takes you to Facebook login, login there takes automatically back to localhost:8080)
 
	* get basic Spring Boot framework with web (ex. command line)
		$ mkdir ui && cd ui
		$ curl https://start.spring.io/starter.tgz -d style=web -d name=simple | tar -xzvf -
	* make space holder for home page by adding index.html to static in resources (skeleton with bootstrap, jquery cmi)
	* add current dependencies for properly load homepage: webjars - jquery, - bootstrap, - locator
	* secure the application by adding dependencies: spring-boot-starter-security (basic) && spring-security-oauth2(social log in)
	* link to Facebook: 
		1. annotate the main with @EnableOAuth2Sso
		2. convert application.properties to application.yml
		
		
		
Template

# SCOIR Technical Interview for Front-End Engineers
This repo contains an exercise intended for Front-End Engineers.

## Instructions
1. Fork this repo.
1. Using technology of your choice, complete [the assignment](./Assignment.md).
1. Update this README with
    * a `How-To` section containing any instructions needed to run/access your system.
    * an `Assumptions` section containing documentation on any assumptions made while interpreting the requirements.
1. Before the deadline, submit a pull request with your solution.

## Expectations
1. Please take no more than 8 hours to work on this exercise. Complete as much as possible and then submit your solution.
1. This exercise is meant to showcase how you work. With consideration to the time limit, do your best to treat it like a production system.
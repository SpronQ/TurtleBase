# TurtleBase case.

![TurtleBase logo](/logo.png)

You are hired as an OPS consultant by TurtleBase. TurtleBase is a company of about 50 people who builds web applications as a core business. 

At the moment there are about 6 web applications live and a couple are being actively worked on. Some of the websites are on a VPS. Some are in a docker container on GCP. Not all of the projects have staging environments but some do. There are also multiple build systems being used for example wercker, CircleCI and Github Actions. Luckelly all the repositories are at Github.

The wish is for all webapps to use the same hosting and CI/CD. There are also some requirements for the future projects. There will be projects that are hosted as microservices using kafka. 

TurtleBase sees cloud vendor lock-in as a big danger to the business and wants to be able to take advantage of the cloud but also be able to move to other cloud providers if needed or self host.

It is your task to propose a setup that fulfills the requirements of the client and propose a migration plan for the existing webapps.

### Summary of requirements:
 - No cloud vendor lock-in
 - Uniform CI/CD system
 - Uniform hosting
 - Can host websites of different sizes
 - Staging environments.
 - Microservice friendly
 - Kafka friendly
 - Migration plan


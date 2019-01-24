# Getting Started 2.1

This repository also contains get started guidelines for the beginners.

This guideline/tutorial aims to be the one-stop shop for getting your hands dirty with Docker. Apart from demystifying the Docker landscape, it'll give you hands-on experience with building and deploying your own webapps on the Cloud. 

You'll be using Amazon Web Services to deploy a static website, and two dynamic webapps on EC2 using Elastic Beanstalk and Elastic Container Service. Even if you have no prior experience with deployments, this tutorial should be all you need to get started.

To manage all of the projects of the tutorial well I split the repository into two, "Getting Started 2.1" will cover static website and one dynamic web app on EC2 using Elastic Beanstalk and "Getting Started 2.2" will cover deploying dynamic multi container based web app on EC2 using Elastic Container Service.

In case if you are too much curious to watch what you are going to play with: 

Just run below command on your terminal and check on your http://localhost:8888/ : 

*docker run -p 8888:80 prakhar1989/static-site*

*docker run -p 8888:5000 russelchowdhury/docker-beginnerguide* Refresh to change the cat gif

Visit my Elastic Beanstalk URL to view the same cat gif deployed: [Cat GIF](http://playrusseldockerapp.eu-west-1.elasticbeanstalk.com/)

Visit my Elastic Container Cluster URL (Will be taken down if bill exceeds the free usage limits, usage on review now) : [SF Food Truck](http://18.202.26.152/)

Too much waste of time so far! So, let's go to the tutorial directly:

[Learn to build and deploy your distributed applications easily to the cloud with Docker](https://docker-curriculum.com/)
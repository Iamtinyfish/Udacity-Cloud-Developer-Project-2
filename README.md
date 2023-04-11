# Udagram Image Filtering

## Link to my Elastic Beanstalk

[http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/](http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/)

### You can test with links

Status 200: [http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i.pinimg.com/736x/71/fe/83/71fe83b3f2423bb24a925ff72565fd0e.jpg](http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i.pinimg.com/736x/71/fe/83/71fe83b3f2423bb24a925ff72565fd0e.jpg)

Status 400: [http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/filteredimage?image_url[]=https://i.pinimg.com/736x/71/fe/83/71fe83b3f2423bb24a925ff72565fd0e.jpg](http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/filteredimage?image_url[]=https://i.pinimg.com/736x/71/fe/83/71fe83b3f2423bb24a925ff72565fd0e.jpg)

Status 400: [http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/filteredimage](http://udacity-cloud-developer-project-2.us-east-1.elasticbeanstalk.com/)

## Github branch

- [master](https://github.com/Iamtinyfish/Udacity-Cloud-Developer-Project-2/tree/master)
- [dev](https://github.com/Iamtinyfish/Udacity-Cloud-Developer-Project-2/tree/dev)

## Run in local

### 1. Run dev

![npm-run-dev](./deployment_screenshots/Dev/npm-run-dev.png)

### 2. Status 200

![status-200](./deployment_screenshots/Dev/status200.png)

### 3. Status 400

![status-400](./deployment_screenshots/Dev/status400.png)

## Deploy

![eb-deploy-status](./deployment_screenshots/ElasticBeanstalkDeployOk.png)
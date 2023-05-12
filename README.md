1. 
### Screenshots (in Markdown README.md) for CI Workflow (Part 1)
Preconfigured Gradle starter workflow
![images1](./images/part1/Screenshot%20(65).png)

Create gradle.yaml
![images2](./images/part1/Screenshot%20(66).png)

Make change to the code and commit to main branch to trigger the action
![images2](./images/part1/Screenshot%20(67).png)

![images2](./images/part1/Screenshot%20(68).png)

![images2](./images/part1/Screenshot%20(69).png)

![images2](./images/part1/Screenshot%20(70).png)

![images2](./images/part1/Screenshot%20(71).png)
2.
### This criterion is linked to a Learning OutcomeScreenshots (in Markdown README.md) for CD Workflow (Part 2)
Create a cluster CMPE172
![images2](./images/part2/Screenshot%20(90).png)

Enable the Kubernetes Engine and Container Registry APIs.
![images2](./images/part2/Screenshot%20(72).png)

Find your GKE Project ID
![images2](./images/part2/Screenshot%20(73).png)

Project ID
![images2](./images/part2/Screenshot%20(74).png)

Create a Service Account for GitHub Access
![images2](./images/part2/Screenshot%20(75).png)

Add the following Cloud IAM roles
![images2](./images/part2/Screenshot%20(76).png)

![images2](./images/part2/Screenshot%20(78).png)

Create a JSON service account keyLinks to an external site. for the service account.
![images2](./images/part2/Screenshot%20(79).png)

Select JSON Key
![images2](./images/part2/Screenshot%20(80).png)

Download JSON Key File
![images2](./images/part2/Screenshot%20(81).png)

![images2](./images/part2/Screenshot%20(82).png)

Configure GitHub Secrets
![images2](./images/part2/Screenshot%20(83).png)

New Repository Secret: GKE_PROJECT
![images2](./images/part2/Screenshot%20(84).png)

![images2](./images/part2/Screenshot%20(85).png)

New Repository Secret: GKE_SA_KEY
![images2](./images/part2/Screenshot%20(86).png)

![images2](./images/part2/Screenshot%20(87).png)

![images2](./images/part2/Screenshot%20(88).png)

Create google.yml
![images2](./images/part2/Screenshot%20(89).png)

Trigger and Deployment to GKE
![images2](./images/part2/Screenshot%20(90).png)

Trigger a CD Deployment by creating a new GitHub Release
![images2](./images/part2/Screenshot%20(91).png)

Create a Release
![images2](./images/part2/Screenshot%20(92).png)

All workflows 2.1 is running
![images2](./images/part2/Screenshot%20(93).png)

Jobs
![images2](./images/part2/Screenshot%20(94).png)

Building
![images2](./images/part2/Screenshot%20(95).png)

Workflow building complete job
![images2](./images/part2/Screenshot%20(96).png)

Workflows build success
![images2](./images/part2/Screenshot%20(97).png)

GKE Workload
![images2](./images/part2/Screenshot%20(98).png)

GKE Services & Ingress
![images2](./images/part2/Screenshot%20(99).png)

GKE Create a Kubernetes Ingress
![images2](./images/part2/Screenshot%20(100).png)

![images2](./images/part2/Screenshot%20(101).png)

Spring Gumball Machine on GKE successfully
![images2](./images/part2/Screenshot%20(102).png)
---
title: "ReactJS Covid Tracker Application Deployment using AWS Services"
date: 2022-03-21
---
❖ We develop the code and store it in local system repository or GitHub repository, can change the code any number of times until it works efficiently.

❖ While developing the code, we can push the code into the S3 Bucket in .zip file format. With Constant Development of code will be pushed into the S3 bucket manually.

❖ AWS CodePipeline uses Jenkins Server which is working on Ec2 instance, it builds the source code into desired format which can integrate with deployment stages.

❖ The Build Artifacts are stored in S3 bucket and Pulled by the CodeDeploy for test stage and production stage on AWS EC2.

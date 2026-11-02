# Docker Demo Project Overview

1. developing a JS app with mongo DB as image from docker hub
2. commit in git
3. commit triggers CI/CD in jenkins
4. jenkins build will produce artifacts, docker image
5. image will be pushed to repository
6. docker image will be deployed on development server that will pull mongo db from docker hub in background
7. login to application and test it
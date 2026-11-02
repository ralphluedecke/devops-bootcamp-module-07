# what is a container

## a container is...
- a way to package application with all the necessary dependencies and configuration
- portable artifact
- easily shared and moved around
- dev and deploy more efficient

## a container lives...
in a container repository
- private within company
- public - docker hub

## application development before containers
- every service installed in OS env
- many steps
- error prone

## application development with containers
- own isolated environment
- package with complete configuration
- one command to install app
- run same app with 2 different versions

## application deployment before containers
- artifact with setup instructions for operations
- installation on OS itself
- dependency version conflicts
- textual guide of deployment
- misunderstandings

## application deployment with containers
- developers and operations work together to package the application in a container
- no environmental configuration needed on server
- only docker runtime

## container implementations
- docker
- containerd
- cri-o


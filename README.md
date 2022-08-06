# Simple Mongo project with kubernetes

Using deployment files - deploy a mongodb and mongo-express each with 1 replica, connect them together and setup mongo to be externally available. Project uses defined config map and secrets. Configmap and secrets have to be applied before applying the deployments and services of mongo and mongo-express.yml
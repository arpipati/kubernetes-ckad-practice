## This challenge is part of the CKAD course by Mumshad Mannambeth on Udemy.


#### Here is the architecture we need to implement:

![Image K8 Wordpress challenge Architecure](https://github.com/apatil-osi/kubernetes-ckad-practice/blob/master/wordpress-mysql-challenge/Screen%20Shot%202020-04-27%20at%201.34.07%20AM.png)


#### NOTE: All imperative commands are included in the individual YAML files.
#### Steps and Order of creation:
* Create services 
  * wp-service.yml
  * mysql-service.yl
* Create Persistent Volumes 
  * wp-pv.yml
  * mysql-pv.yml
* Create Persistent Volume Claims 
  * wp-pvc.yml
  * mysql-pvc.yml
* Create Secret 
  * mysql-pass.yml
* Create Deployments 
  * wp-deployment.yml
  * mysql-deployment.yml

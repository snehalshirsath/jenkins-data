# NFS mount for jenkins backup on GCP

installed jenkins on vm on google cloud. 
created nfs server to backup jenkins master.
created autoscaling group with that vm for High Availability.

jenkins with file store

1) create nfs server through gcp console
2) create folder sructure on vm : mkdir /var/lib/jenkins
3) install nfs on VM
4) mount nfs with : /var/lib/jenkins
5) install jenkins on that VM
6) create jenkins machine image from VM
7) create instance template from image and add user data while creating template
8) create instance group using that instance template.

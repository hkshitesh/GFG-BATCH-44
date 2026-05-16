## CMD Command to Connect with EC2 from your CMD
  ssh -i gfgkey.pem ec2-user@13.203.155.134


## Jenkins Setup

  1. JDK 17 Download and Install Link
     https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
  2. Downlaod and Install Jenkins
     https://www.jenkins.io/download/
  


EKS Cluster Connection Commands

  aws eks --region ap-south-1 describe-cluster --name gfgCluster --query cluster.status
  
  aws eks --region ap-south-1 update-kubeconfig --name gfgCluster

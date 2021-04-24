# Infra_Optimization
------------------------------------------------
Infrastructure-Optimization.docx
------------------------------------------------

1. Create the cluster (EC2 instances with load balancer and elastic IP in case of AWS)

2. Automate the provisioning of an EC2 instance using Ansible 

3. Install Docker and Kubernetes on the cluster

4. Implement the network policies at the database pod to allow ingress traffic from the front-end application pod

5. Create a new user with permissions to create, list, get, update, and delete pods

6. Configure application on the pod

7. Take snapshot of ETCD database

8. Set criteria such that if the memory of CPU goes beyond 50%, environments automatically get scaled up and configured


-----------------------------------------------------
Yaml Files used to Optimize the Infrastructure 
-----------------------------------------------------

cluster.yaml => Ansible Script for Provision

networkpolicy.yaml => Allow ingress traffic from the front-end application pod

userrole.yaml => Create User with Permission

pod.yaml => Configure Application on the POD 

HorizontalPodAutoscaler.yaml => POD Autoscaler if CPU Goes beyond 50%

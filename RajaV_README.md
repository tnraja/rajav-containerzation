
# MERN stack e-commerce application (shopNow) using Kubernetes, Helm charts, and Jenkins CI/CD pipeline

# Clone Repo - https://github.com/mohanDevOps-arch/shopNow

# VM Structure

<img width="940" height="362" alt="image" src="https://github.com/user-attachments/assets/7493e191-719b-440b-923a-e91f2bfcd373" />

# Kubernetes Manifests file creations and Deployment

1. Frontend
   
2. Backend
   
3. MongoDB

<img width="940" height="79" alt="image" src="https://github.com/user-attachments/assets/c09f362f-8065-4777-aacd-0199449a0088" />

 <img width="940" height="74" alt="image" src="https://github.com/user-attachments/assets/2dd81559-84a6-4b96-8c96-a5ef52975096" />

  <img width="940" height="98" alt="image" src="https://github.com/user-attachments/assets/69165b90-c6e0-4585-8185-8111024dd932" />

   <img width="940" height="88" alt="image" src="https://github.com/user-attachments/assets/ccbe69f9-f4eb-43df-81c4-c60e553a75dd" />

   # HELM Creations 

   <img width="940" height="151" alt="image" src="https://github.com/user-attachments/assets/78e16484-67ae-4a9b-863f-8f7280fe9ed9" />

<img width="940" height="235" alt="image" src="https://github.com/user-attachments/assets/56e32d08-20d9-4f24-a664-9237e05672c7" />

# Kubernetes Creations 

<img width="940" height="189" alt="image" src="https://github.com/user-attachments/assets/56d6591b-0186-4c44-8eaa-7cf2d14f1cb4" />

# ECR Repo Creation

<img width="1901" height="911" alt="image" src="https://github.com/user-attachments/assets/512933c4-7236-4e87-a835-b4a176d790e4" />

# Final Message

### 1. Minikube Storage Requirement
Minikube requires a minimum of **20 GB disk space** to start the cluster.  
The current environment does not have sufficient storage, which prevents Minikube from running.

### 2. Pod Deployment Issue
Due to the Minikube cluster not starting successfully, Pods are unable to run.

<img width="940" height="470" alt="image" src="https://github.com/user-attachments/assets/149c3871-7abe-450a-8763-85520aebdcf0" />

### 3. Unable to Create EKS Cluster
While attempting to create the EKS cluster in AWS, the process fails due to configuration and permission limitations.

<img width="1906" height="887" alt="image" src="https://github.com/user-attachments/assets/a40f34e2-5760-48f5-80cd-a656a2677337" />

### 4. IAM Role Creation Issue
Unable to create a new IAM role from the Ubuntu environment while configuring AWS CLI.

<img width="1887" height="945" alt="image" src="https://github.com/user-attachments/assets/11da8d07-cb5d-4cc1-9648-4292e55cc371" />

## Conclusion
Due to storage limitations and IAM permission issues, the Kubernetes cluster and AWS EKS setup could not be completed successfully. Further environment configuration is required to proceed.

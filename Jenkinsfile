pipeline {
    agent any
    
    environment {
        // YOUR AWS ACCOUNT ID + ECR URI
        ECR_REGISTRY = '975050024946.dkr.ecr.us-east-1.amazonaws.com'
        
        // YOUR EKS CLUSTER NAME (or Minikube for testing)
        CLUSTER_NAME = 'shopnow-cluster'  // Change to your EKS name
        
        // AWS Region
        AWS_REGION = 'us-east-1'
        
        // Helm chart path
        HELM_CHART_PATH = './shopnow-chart'
    }
    
    stages {
        stage('Checkout') {
            steps

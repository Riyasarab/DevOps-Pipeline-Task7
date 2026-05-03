pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo "Building the project using Maven tool" }
        }
        stage('Unit Tests') {
            steps { echo "Executing unit tests using JUnit framework" }
        }
        stage('Integration Tests') {
            steps { echo "Running integration tests using Selenium tool" }
        }
        stage('Code Analysis') {
            steps { echo "Performing code analysis using SonarQube tool" }
        }
        stage('Security Scan') {
            steps { echo "Scanning for vulnerabilities using OWASP Dependency-Check tool" }
        }
        stage('Deploy to Staging') {
            steps { echo "Deploying the application to AWS EC2 staging environment" }
        }
        stage('Deploy to Production') {
            steps { echo "Deploying the application to AWS EC2 production environment" }
        }
    }
}

pipeline {
    agent any
    
    // Jenkins pipeline for SIT753 7.1C

    stages {

        stage('Build') {
            steps {
                echo 'Build the code using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit and integration tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse the code using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scan the code for vulnerabilities using OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy the application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on the staging environment using Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy the application to AWS EC2 production server'
            }
        }
    }
}
// Automatic trigger verification

pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building and packaging the application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running unit and integration tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analysing code quality using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning the application for vulnerabilities using OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying the application to an AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests on the staging environment using Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying the application to an AWS EC2 production server'
            }
        }
    }
}

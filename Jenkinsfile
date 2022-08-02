#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            filename 'Dockerfile'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'npm test'
            }
        }
    }
}i

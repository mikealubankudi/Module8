#!/usr/bin/env groovy

pipeline {
    agent none
    stages {
        stage('build') {
            when {
                expression {
                    BRANCH_NAME == 'master'
            steps {
                script {
                    echo "Building the application..."
                }
            }
        }
        stage('test') {
            steps {
                script {
                    echo "Testing the application..."
                }
            }
        }
        stage('deploy') {
            steps {
                script {
                    echo "Deploying the application..."
                }
            }
        }
    }
}

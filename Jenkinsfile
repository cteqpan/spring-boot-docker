#!/usr/bin/env groovy

pipeline {

    agent any

    stages {
        stage('Clean') {
            steps {
                echo 'Cleaning...'
                sh './gradlew clean'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh './gradlew build'
            }
        }
    }
}

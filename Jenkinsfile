pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
					#!/bin/bash
					echo "check 1"
                   			cd test_central
					make
					'''
            }
        }
    }
}

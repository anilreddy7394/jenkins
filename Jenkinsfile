pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh '''
					#!/bin/bash
					echo "check 1"
					git clone https://github.com/anilreddy7394/test_central.git
                   			cd test_central
					make
					'''
            }
        }
    }
}

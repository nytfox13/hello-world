pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''#!/bin/bash

echo "Starting build"'''
          }
        }
        stage('Run test') {
          steps {
            sh '''#!/bin/bash

echo "Hello world"'''
          }
        }
      }
    }
  }
}
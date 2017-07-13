#!/usr/bin/env groovy


pipeline {
  agent any
	tools {
        maven 'MAVENAut'
        }
  stages {
    stage('build') {
      steps {
        sh 'mvn package'
        }
    }
    stage('run') {
      steps {
		echo env.JOB_NAME
		
      }
    }
  }
}
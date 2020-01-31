#!groovy

pipeline {
 agent any
 stages {
   stage('checkout') {
     steps {
      sh 'git clone https://github.com/anil2406/dev1.git'
      }
      }
   stage('datadog agent installation') {
     steps {
      sh 'ansible-playbook -vvv dd_agent.yml'
      }
      }
      }
      }

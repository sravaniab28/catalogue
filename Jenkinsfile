pipeline {
    agent { node { label'AGENT-1' } }
    stages {
        stage('Istall dependenicies') {
            steps {
              sh 'npm install'
            }
        }
         stage('Unit test') {
             steps {
                echo "unit testing is done here"
            }
        } 
         stage('sonar scan') {
             steps {
                sh 'ls -ltr'
                sh 'sonar-scanner'
             }
        }     
    }
}
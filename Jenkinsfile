pipeline {
    agent { node { label 'AGENT-1' } }
    stages {
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('unit test') {
            steps {
                echo "unit testing is done here"
            }
        }
    } 
}
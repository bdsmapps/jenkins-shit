pipeline {
    agent {
        node {
            label "master"
        }
    }
    stages {
        stage('Clone repo') {
            steps {
                cleanWs()
                checkout scm
            }
        }
      stage('Run tests') {
        steps {

            sh label: '', script: 'echo fucking awesome run tests ${TESTS}'             
          }      
      }
      
    }
}

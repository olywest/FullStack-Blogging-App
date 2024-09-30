pipeline {
    agent any
    
    tools {
        maven 'mav' 
        jdk 'jdk17'
    }

    stages {

        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
              
        stage('Package') {
            steps {
                sh "mvn package"
            }
        }
    }
}

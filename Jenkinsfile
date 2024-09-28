pipeline {
    agent any
    
    tools {
        maven 'mav'
        jdk 'jdk17'
    }

    stages {     
        
        stage('Compile') {
            steps {
            sh  "mvn compile"
            }
        }
              
        stage('Package') {
            steps {
                sh "mvn package"
            }
        }
    }
}

pipeline {
    agent any
    
    tools {
        maven 'maven3'
        jdk 'jdk21'
    }
     stages {    
        stage('Test') {
            steps {
                sh "mvn test"
            }
        }
        
        
    }
}

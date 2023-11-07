pipeline {
    agent any
 tools {
        maven 'local_maven'
    }

    stages {
        
        stage('build') {
            steps {
                bat 'mvn clean package'
            }
                
        }
    }
}

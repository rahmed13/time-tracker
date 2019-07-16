pipeline {
    agent any 
    stages {
        stage('Clean') { 
            steps {
                bat "mvn clean"
            }
        }
        stage('compline') { 
            steps {
                bat "mvn compile"
            }
        }
        stage('test') { 
            steps {
               bat "mvn test"
            }
        }
                stage('package') { 
            steps {
               bat "mvn package"
            }
        }
    }
}

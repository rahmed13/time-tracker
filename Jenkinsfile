pipeline {
    agent any 
    stages {

        stage('compline') { 
            steps {
                bat "mvn compile"
            }
        }

                stage('package') { 
            steps {
               bat "mvn package"
            }
        }
    }
}

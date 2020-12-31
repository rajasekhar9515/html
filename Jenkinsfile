pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('compile') { 
            steps {
                sh "compile" 
            }
        }
        stage('test') { 
            steps {
                sh "mvn test"
            }
        }
       stage('package') { 
            steps {
                sh "package" 
            }
        }
}
}

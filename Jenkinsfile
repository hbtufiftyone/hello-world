pipeline {
    agent any
    tools{
        maven '3.6.3'
    }
    stages {
        stage('Test stage') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

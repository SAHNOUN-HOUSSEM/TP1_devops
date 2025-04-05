pipeline {
    agent any

    tools {
        maven 'Maven3' // This should match the name you configured in Jenkins
    }

    stages {

        stage('Build with Maven') {
            steps {
                sh 'mvn clean install'
            }
        }


    }
}
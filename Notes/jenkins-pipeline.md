Jenkins/basic-pipeline/Jenkinsfile

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
            }
        }
    }
}

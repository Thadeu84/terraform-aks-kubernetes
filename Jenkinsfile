pipeline {
    agent any

    stages {
        stage ('Build Image') {
            steps {
                script {
                    dockerapp = docker.build("devopsguimaraes/api-produto", '-f ./../src/Dockerfile ./src') 
                }
            }
        }
    }
}
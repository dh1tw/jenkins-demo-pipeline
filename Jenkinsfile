env.DOCKER_HOST = 'unix:///var/run/docker.sock'

pipeline {
    agent {
        docker { 
          image 'python:3.11' 
        }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

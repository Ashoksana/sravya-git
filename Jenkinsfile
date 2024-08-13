pipeline {
    agent any

    stages {
        stage('Docker install') {
            steps {
                sh 'sudo apt install docker.io -y'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

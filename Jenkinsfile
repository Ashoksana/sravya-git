pipeline {
    agent any

    stages {
        stage('Create a file') {
            steps {
                sh 'cd ~/ && touch sateesh.txt'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

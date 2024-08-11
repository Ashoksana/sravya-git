pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                sh 'cd ~ && git clone -b main https://github.com/Ashoksana/sravya-git.git'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

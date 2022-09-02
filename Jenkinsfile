pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('version') {
            steps {
                bat 'python --version'
            }
            }
        
    }
}

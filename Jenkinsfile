pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello Jenkins Pipeline'
            }
        }

        stage('Test') {
            steps {
                sh 'pwd'
                sh 'whoami'
                sh 'hostname'
            }
        }
    }
}

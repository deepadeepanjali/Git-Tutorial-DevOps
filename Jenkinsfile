pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Run Build'
            }
        }
        stage('Test') {
            steps {
                input('Do you want to proceed?')
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
                sleep 5
            }
        }
        stage('build') {
            steps {
                echo 'build'
                sleep 10
            }
        }
        stage('test') {
            steps {
                echo 'test'
                sleep 5
            }
        }
        stage('QA') {
            steps {
                echo 'QA'
                sleep 5
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy'
                sleep 5
            }
        }
    }
}

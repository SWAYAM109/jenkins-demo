pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'chmod +x hello.sh'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project...'
                sh './hello.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project...'
            }
        }
    }
}

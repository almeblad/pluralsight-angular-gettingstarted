pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                withNPM(npmrcConfig:'MyNpmrcConfig') {
                echo "Performing npm build..."
                sh 'npm install'
        }
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
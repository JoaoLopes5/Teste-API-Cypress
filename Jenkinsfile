pipeline {
    agent any

    stages {
        stage('Setup') {
            steps {
                git branch: 'main', url: 'https://github.com/EBAC-QE/ebac-cypress-samples.git'
                sh 'npm install'
            }
        }
               stage('Test') {
            steps {
                sh '''set NO_COLOR=1
npm test'''
            }
        }
    }
}

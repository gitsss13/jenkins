pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/gitsss13/jenkins.git'
            }
        }

        stage('Print Directory') {
            steps {
                bat 'cd'
            }
        }
    }
}
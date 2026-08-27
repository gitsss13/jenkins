pipeline {
 agent any
    stages {
        stage('Checkout Code') {
            steps {
              git branch: 'main', url: 'https://github.com/gitsss13/jenkins.git'
            }
        }
        stage('Create File') {
            steps {
              bat 'echo This file is created by Jenkins > demo.txt'
            }
        }
    }
}

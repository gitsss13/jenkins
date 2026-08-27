pipeline {
 agent any
    stages {
       stage('Checkout Code') {
            steps {
               git branch: 'main', url:'https://github.com/gitsss13/jenkins.git'
            }
        }
        stage('Read File') {
            steps {
               bat 'type README.md'
            }
        }
    }
}

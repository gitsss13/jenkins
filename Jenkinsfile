pipeline {
 agent any
 stages {
 stage('Checkout Code') {
 steps {
 git 'https://github.com/gitsss13/jenkins.git'
 }
 }
 stage('Show Files') {
 steps {
 bat 'dir'
 }
 }
 }
}
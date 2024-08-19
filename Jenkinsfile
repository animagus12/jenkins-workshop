
pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                echo 'Hello World - Development'
                bat 'git clone "https://github.com/animagus12/jenkins-workshop.git"'
            }
        }
        
        stage('QA') {
            steps {
                echo 'Hello World - QA'
            }
        }
        
        stage('UAT') {
            steps {
                echo 'Hello World - UAT'
            }
        }
        
        stage('Pre- Prod') {
            steps {
                echo 'Hello World - Pre Prod'
            }
        }
    }
}

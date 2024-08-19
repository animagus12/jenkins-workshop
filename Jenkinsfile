
pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                echo 'Hello World - Development'
                bat 'cd "C:\\Users\\offic\\Downloads\\Training"'
                bat 'git clone "https://github.com/animagus12/jenkins-workshop.git"'
            }
        }
        
        stage('QA') {
            steps {
                echo 'Hello World - QA'
                bat 'cd "C:\\Users\\offic\\Downloads\\Training"'
                bat 'mkdir "Apple Folder"'
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

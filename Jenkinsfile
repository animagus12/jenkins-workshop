
pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                echo 'Hello World - Development'
                // bat 'cd "C:\\Users\\offic\\Downloads\\Training"'
                // bat 'git clone "https://github.com/animagus12/jenkins-workshop.git"'
            }
        }
        
        stage('QA') {
            steps {
                echo 'Hello World - QA'
                script {
                    // Define the folder path
                    def folderPath = "C:/Users/offic/Downloads/Training"

                    // Create the folder if it doesn't exist
                    if (!fileExists(folderPath)) {
                        sh "mkdir -p ${folderPath}"
                        echo "Folder created at ${folderPath}"
                    } else {
                        echo "Folder already exists at ${folderPath}"
                    }
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

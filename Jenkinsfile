pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                bat 'npm install'
                echo '------------'
            }
        }
        stage('Run script'){
            steps {
                echo 'run scripting'
                script {
                    powershell 'C:\\Users\\admin01\\Documents\\example_script.ps1'
                } 
                echo '------------'

            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('Checking python version') {
            steps {
                bat 'python -V'
            }
        }
        stage('REPO cloning') {
            steps {
                bat 'XCOPY \S "*" "C:/xampp/htdocs/jenkins-pipline" /Y'
            }
        }
        stage('Confirm') {
            steps {
                echo 'Done!'
            }
        }
    }
}
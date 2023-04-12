pipeline {
    agent any
    stages {
        stage('Checking python version') {
            steps {
                bat 'py -V'
            }
        }
        stage('REPO cloning') {
            steps {
                bat 'xcopy /S "*" "C:/xampp/htdocs/jenkins_pipline" /Y'
            }
        }
        stage('Confirm') {
            steps {
                echo 'Done!'
            }
        }
    }
}
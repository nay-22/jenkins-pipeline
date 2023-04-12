pipeline {
    agent any
    stages {
        stage('Display Context') {
            steps {
                echo 'Experiment 4 - Jenkins Pipeline'
            }
        }
        stage('REPO cloning') {
            steps {
                bat 'xcopy \S "*" "C:/xampp/htdocs/jenkins_pipline" /Y'
            }
        }
        stage('Confirm') {
            steps {
                echo 'Done!'
            }
        }
    }
}
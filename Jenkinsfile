pipeline {
    agent any

    environment {
        COMSPEC = 'C:\\Windows\\System32\\cmd.exe'
    }

    stages {
        stage('Compile Java') {
            steps {
                bat 'javac Hello.java'
            }
        }

        stage('Run Java') {
            steps {
                bat 'java Hello'
            }
        }
    }
}

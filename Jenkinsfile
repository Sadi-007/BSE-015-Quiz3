pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'C:\\Windows\\System32\\cmd.exe /c javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                bat 'C:\\Windows\\System32\\cmd.exe /c java Hello'
            }
        }
    }
}

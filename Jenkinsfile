pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                bat 'C:\\Windows\\System32\\cmd.exe /c javac Hello.java'
            }
        }

        stage('Run Java') {
            steps {
                bat 'C:\\Windows\\System32\\cmd.exe /c java Hello'
            }
        }
    }
}

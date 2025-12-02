pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                powershell '"C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe" -Command "javac Hello.java"'
            }
        }
        stage('Run') {
            steps {
                powershell '"C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe" -Command "java Hello"'
            }
        }
    }
}

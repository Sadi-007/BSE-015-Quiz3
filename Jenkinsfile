pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                powershell 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                powershell 'java Hello'
            }
        }
    }
}

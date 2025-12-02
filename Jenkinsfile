pipeline {
    agent any

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

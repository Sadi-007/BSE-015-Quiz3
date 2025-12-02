pipeline {
    agent any

    stages {
        stage('Compile Java') {
            steps {
                sh 'javac Hello.java'
            }
        }

        stage('Run Java') {
            steps {
                sh 'java Hello'
            }
        }
    }
}

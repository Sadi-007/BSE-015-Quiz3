pipeline {
    agent any

    stages {
        stage('Run Python') {
            steps {
                powershell '"C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe" -Command "py script.py"'
            }
        }
    }
}

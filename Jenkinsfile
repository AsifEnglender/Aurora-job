pipeline {
    agent any

    stages {
        stage('Clone repository') {
            steps {
                git branch: 'main', url: 'https://github.com/AsifEnglender/Aurora-job'
            }
        }

        stage('Run Python script') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Clone repository') {
            steps {
                git 'https://github.com/AsifEnglender/Aurora-job'
            }
        }

        stage('Run Python script') {
            steps {
                sh 'python main.py'
            }
        }
    }
}

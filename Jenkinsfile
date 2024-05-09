pipeline {
    agent any

    stages {
        stage('Clone repository') {
            steps {
                git 'https://github.com/Muhammad-Ali-70/JenkenDemo.git'
            }
        }
        stage('Run Code') {
            steps {
                sh 'python Project.py'
            }
        }
    }
}

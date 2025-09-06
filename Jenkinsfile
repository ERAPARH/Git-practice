pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...'
                git branch: 'main', url: 'https://github.com/ERAPARH/Git-practice.git'
            }
        }

        stage('Run Python Script') {
            steps {
                echo 'Running hello.py...'
                sh 'python3 hello.py'
            }
        }
    }
}

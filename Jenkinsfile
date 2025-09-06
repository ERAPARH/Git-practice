pipeline{
    agent any
    stages{
        stage('Clone Repository'){
            steps{
                echo 'Cloning Repository...'
                // Git repo se code pull kro 
                git branch: 'main', https://github.com/ERAPARH/Git-practice
            }
        }

        stage('Run Python script'){
            steps{
                echo 'Running hello.py...'
                sh 'python3 hello.py' 
                
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/sameerzemi/HelloWorld.git'
            }
        }

        stage('Run Script') {
            steps {
                bat 'python hello.py'  // For Windows
                // sh 'python3 hello.py'  // Use this if running on Linux
            }
        }
    }
}

pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac HelloWorld.py'
            }
        }

        stage('Run') {
            steps {
                sh 'python HelloWorld'
            }
        }
    }
}

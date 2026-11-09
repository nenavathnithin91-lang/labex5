pipeline {
    agent any

    stages {

        stage('Compile') {
            steps {
                echo 'Checking Python Program'
                sh 'python3 -m py_compile HelloWorld.py'
            }
        }

        stage('Run') {
            steps {
                echo 'Executing Python Program'
                sh 'python3 HelloWorld.py'
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('Create python script') {
            steps {
            sh "chmod +x ./create-python-test"
            sh "touch python-test.py"
            }
        }   
        stage('Run python script') {
            steps {
            sh 'python3 python-test.py'
            }
        }
    }       
}

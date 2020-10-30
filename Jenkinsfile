pipeline {
    agent any
    stages {
        stage('Create python script') {
            steps {
          
            sh "touch python-test.py"
            sh "chmod +x ./create-python-test/python-test.py"
            }
        }   
        stage('Run python script') {
            steps {
            sh 'python3 python-test.py'
            }
        }
    }       
}

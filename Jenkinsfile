pipeline {
    agent any
    stages {
        stage('Make python script') {
            steps {
            sh "chmod +x ./scripts/make-python.sh"
            sh "./scripts/make-python.sh"
            }
        }   
        stage('Run python script') {
            steps {
            sh 'python3 helloworld.py'
            }
        }
    }       
}

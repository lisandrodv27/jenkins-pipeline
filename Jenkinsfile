pipeline {
    agent any
    stages {
        stage('Make python script') {
            steps {
            sh 'touch helloworld.py'
            }
        }   
        stage('Run python script') {
            steps {
            sh 'python3 helloworld.py'
            }
        }
    }       
}

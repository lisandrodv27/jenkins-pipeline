pipeline {
    agent any
    stages {
        stage('Make python script') {
            steps {
            sh 'touch helloworld.py'
            sh 'echo "print('hello world')"'
            sh 'echo "print('hello world')" > helloworld.py'
            }
        }   
        stage('Run python script') {
            steps {
            python3 helloworld.py
            }
        }
    }       
}

pipeline {
    agent any
    stages {
        stage('Make python script') {
            steps {
            sh "chmod +x ./make-groovy-test"
            sh "touch groovy-test.sh"
            }
        }   
        stage('Run python script') {
            steps {
            sh 'groovy groovy-test.sh'
            }
        }
    }       
}

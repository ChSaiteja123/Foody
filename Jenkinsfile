pipeline {
    agent any
    stages {
        stage('Pull docker image') {
                steps{
                    script {
                        sh 'docker pull saitejch/ecomm-app'
                    }
                }
        }
    }
}

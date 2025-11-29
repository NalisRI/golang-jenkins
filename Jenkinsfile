pipeline {
     agent{
                docker {
                    image 'golang:1.25'
                }
        }

    stages {
        stage('go docker') {

            steps {
                sh 'go version'
            }
        }


    }
}

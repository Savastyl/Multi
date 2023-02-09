pipeline {
    agent any

    stages {

        stage('checkout codes ') {
            steps {
              sh "git clone git://github.com/Savastyl/RealWorld-Application-CI-CD-Using-Azure-DevOps-Jenkins-GitHub-Actions.git"

            }
        }
        stage('build docker') {
            steps {
                echo 'building docker'
                sh 'docker build -t test-pipeline .'
            }
        }
    }
}

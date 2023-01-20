pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'test'
            }
        }
        stage('Test') {
            steps {
                echo 'this is test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is deploy'
                
            }
        }
        post{
            always{
                emailext body: 'summary', subject: 'Jenkinpipeline', to: 'gnavyasree2001@gmail.com'
            }
        }
    }
}

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
          
         }
       post
           {
              always
              {
                 emailext body: 'summary', replyTo: 'ganvayasree2001@gmail.com', subject: 'jenkinspipeline', to: 'gnavyasree2001@gmail.com'
              }
           }
}

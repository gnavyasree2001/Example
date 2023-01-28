pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'test'//commit
            }
        }
        stage('Test') {
            steps {
                echo 'this is test'//comment
            }
        }
        stage('Deploy') {
            steps {
                echo 'This is deploy'//this is deploy stage
                
            }
        }
          
         }
       post//post
           {
              always
              {
                 emailext body: 'summary', replyTo: 'ganvayasree2001@gmail.com', subject: 'jenkinspipeline', to: 'gnavyasree2001@gmail.com'//this is post line
              }
           }
}

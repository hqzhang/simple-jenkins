#!/user/bin/env groovy

node('master'){
    try {
        stage('build'){
           checkout scm
           sh "echo 'I am in build'"
           sh "echo 'just for building'"

     }
    
        stage('test'){
           sh "echo 'I am in test'"
           sh "echo 'just for testing'"
        }
        stage('deploy'){
           sh "echo 'I am in deploy'"
           //ansible-book


       }
   } catch(error) { 
       throw error

   } finally {



  }




}

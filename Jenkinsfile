#!/user/bin/env groovy

node('master'){
    try {
        stage('build'){
           checkout scm
           sh "ls"
           sh "echo 'just for building'"

     }
    
        stage('test'){
           sh "ls -al"
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

pipeline {
  agent any 
  stages {
      stage('Hello') {
       steps {
          echo "Hello"
         }
       }
       stage('readme'){
         when{
           branch "fix*"
       }
       steps {
         sh '''
           cat README.md
        '''
      }
  }
}

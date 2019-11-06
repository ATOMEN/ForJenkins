#!groovy

pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
      stage('Test') {
         steps {
            echo 'Now I am testing'
         }
      }
   }
   post
   {
      always {
         echo 'Post activity run.'
      }
   }
}

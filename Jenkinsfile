pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               run conda activate env34 && pyhton manage.py runserver
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}

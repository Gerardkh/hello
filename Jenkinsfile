pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''mkdir hello
mv hello.py requirements.txt hello
tar -czvf flask_hello.tar.gz hello'''
      }
    }
  }
}
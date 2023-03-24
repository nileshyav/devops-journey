pipeline {
  agent any
  stages {
    stage('test aws cred') {
      steps {
        s3Upload(bucket: 'nilesh-2023-testing', acl: 'PublicRead', file: 'hello.txt', text: 'Hello India')
      }
    }

  }
}
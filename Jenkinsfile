pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(installation: 'C:\\Program Files (x86)\\Apache Software Foundation\\apache-ant-1.9.13\\bin', jdk: 'C:\\Program Files (x86)\\Java\\jdk1.8.0_181\\bin')
      }
    }
    stage('') {
      steps {
        mail(subject: 'Buil', body: 'Buil', bcc: 'rajesh094780@gmail.com', cc: 'rajesh094780@gmail.com', from: 'rajesh094780@gmail.com', replyTo: 'rajesh094780@gmail.com', to: 'rajesh094780@gmail.com', mimeType: 'text/html', charset: 'UTF-8')
      }
    }
  }
}
pipeline {
  agent any
    stages {
      stage('Build') {
        steps {
          awsCodeBuild projectName: 'code-deploy-reinvent',
                       credentialsId: 'codebuid',
                       credentialsType: 'jenkins',
                       region: 'us-east-2',
                       sourceControlType: 'project'

        }
      }
    }
}
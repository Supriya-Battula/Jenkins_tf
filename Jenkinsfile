pipeline {
  agent { label ''}

  stages {
    stage ('build') {
      steps {
        git url: "",
        branch: 'main'
      }
    }
    stage ('steps') {
      steps {
        sh 'terraform init'
        sh 'terraform apply -auto-approve'
      }
     }
    }
}

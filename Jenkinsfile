pipeline {
  agent { label 'JDK_TF'}

  stages {
    stage ('build') {
      steps {
        git url: "https://github.com/Supriya-Battula/Jenkins_tf.git",
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

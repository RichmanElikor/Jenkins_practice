pipeline {
  agent any 

  stages {
    stage('checkout'){
      steps {
        echo "Cloning repo...."
      }
    }

    stage('Build'){
      steps{
        echo 'Running build script....'
        sh 'echo Hello, Jenkins'
      }
    }

    stage('Test'){
      steps{
        echo 'Running tests....'
        sh 'echo Tests passed'
      }
    }
  }
}
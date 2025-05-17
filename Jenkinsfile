pipeline {
  agent any 

  stages {
    stage('checkout'){
      steps {
        echo "Cloning repo...."
        https://github.com/RichmanElikor/Jenkins_practice.git
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
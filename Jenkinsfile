pipeline {
  agent any
  stages {
    stage( "Build" ) {
        bat ' git clone https://github.com/anautiyal1/ghost-1.git'
                bat 'npm install ghost-cli -g'
      steps {
        echo 'Building'
      }
    }
    stage ('Test') {
      steps {
        echo 'Testing'
      }
    }
    stage ('Deploy'){
      steps {
        echo 'Deploying'
      }
    }
  }
}
    

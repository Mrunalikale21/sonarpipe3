pipeline{
  agent any
  stages{
    stage('Built'){
      steps{
        echo "i am bulding"
      }
    }
    stage('test'){
      steps{
        echo "i am testing"
      }
    }
    stage('Deploy'){
      steps{
        echo "Deploying"
      }
    }
  }
  post{
    success{
      echo 'your pipeline is success'
    }
    failure{
      echo 'Pipeline failed'
    }
  }
}

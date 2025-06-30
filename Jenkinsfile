pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        echo 'compile app'
        sh 'npm run build'
      }
    }
    stage('test'){
      steps{
        echo 'test app'
        sh 'npm test'
      }
    }
  }
}

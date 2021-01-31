pipeline{
  agent any
  stages {
    stage("build"){
      steps{
        sh 'test_first.py'
      }
    }
    stage('test') {
      steps {
        sh 'test_first.py'
      }
    }
  }
}
      

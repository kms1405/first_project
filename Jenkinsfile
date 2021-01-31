pipeline{
  agent any
  stages {
    stage("build"){
      steps{
        sh '/script.sh'
      }
    }
    stage('test') {
      steps {
        sh 'test_first.py'
      }
    }
  }
}
      

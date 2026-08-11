Pipeline{
  agent any
  stages{
    stage('compile'){
      steps{
        sh 'java HelloWorld.java'
      }
    }
    stage('Run'){
      steps{
        sh 'java HelloWorld'
      }
    }
  }
}

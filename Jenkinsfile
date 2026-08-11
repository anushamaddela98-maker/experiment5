Pipeline{
  agent any
  stages{
    stage('Compile'){
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

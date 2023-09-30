pipeline{
  agent any
  stages{
    stage('SCM THE PROJECT FROM GITHUB')
    { 
      steps{
     git 'https://github.com/yankils/hello-world.git'
      }
    }
    stage('Building the project')
    {
      steps{
        sh 'mvn clean package'
      }
    }
  }
}

pipeline{
  agent any
  stages{
    stage{'SCM THE PROJECT FROM GITHUB'}
    { 
      steps{
        sh 'git clone https://github.com/pranshu-paliwal/hello-world.git'
      }
    }
    stage{'Building the project'}
    {
      steps{
        sh 'mvn clean package'
      }
    }
  }
}

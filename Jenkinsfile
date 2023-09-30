pipeline{
  agent any
  stages{
    stage{'SCM THE PROJECT FROM GITHUB'}
    { 
      steps{
        git 'https://github.com/pranshu-paliwal/hello-world.git'
      }
    }
    stage{'Building the project'}
    {
      steps{
        mvn clean package
      }
    }
  }
}

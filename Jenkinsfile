node
{
  stage('Initialize')
   {
    def dockerHome = tool 'myDocker'
    sh "echo $dockerHome"
    sh "ls $dockerHome/bin/"
   }
  stage('Checkout')
  {
    checkout scm
  }
 
  stage('Image build')
  {
    echo "hello"
    
    sh "docker build -t ubuntudemo ."
  }

}


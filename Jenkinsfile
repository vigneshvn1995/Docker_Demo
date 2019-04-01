node
{
  stage('Initialize')
   {
    def dockerHome = tool 'myDocker'
    env.PATH = "${dockerHome}/bin:${env.PATH}"
    sh "docker info"
   }
  stage('Checkout')
  {
    checkout scm
  }
 
  stage('Image build')
  {
    echo "hello"
    
  }

}


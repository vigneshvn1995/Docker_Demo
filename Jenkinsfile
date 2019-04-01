node
{
  stage('Initialize')
   {
    def dockerHome = tool 'myDocker'
    env.PATH = "${dockerHome}/bin:${env.PATH}"
   }
  stage('Checkout')
  {
    checkout scm
  }
 
  stage('Image build')
  {
    echo "hello"
    sh "docker build -t ubuntudemo  -t ubuntudemo --pull --no-cache ."
  }

}


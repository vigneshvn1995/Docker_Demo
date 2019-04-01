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
    sh "sudo usermod -a -G docker jenkins"
    sh "docker build -t ubuntudemo ."
  }

}


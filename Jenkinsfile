node
{
  stage('Checkout')
  {
    checkout scm
  }
  
  stage('Initialize')
   {
      def dockerHome = tool name: 'docker', type: 'org.jenkinsci.plugins.docker.commons.tools.DockerTool'
      def dockerCMD = "${dockerHome}/bin/docker"
      sh "${dockerCMD} build -t ubuntudemo ."
   }
  
 
  stage('Image build')
  {
    echo "hello"
    
  }

}


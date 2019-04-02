node
{
  stage('Initialize')
   {
      def dockerHome = tool name: 'docker', type: 'org.jenkinsci.plugins.docker.commons.tools.DockerTool'
      def dockerCMD = "${dockerHome}/bin/docker"
      sh 'chmod 777 /var/run/docker.sock'
      sh "${dockerCMD} build -t ubuntudemo ."
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


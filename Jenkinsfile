node
{
  stage('Initialize')
   {
    def dockerHome = tool name: 'docker-3', type: 'org.jenkinsci.plugins.docker.commons.tools.DockerTool'
    def dockerCMD = "${dockerHome}/bin/docker"
     sh "${dockerCMD} info"
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


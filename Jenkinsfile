node
{
  stage('Initialize')
   {
    def dockerHome = tool 'myDocker'
    env.PATH = "${dockerHome}/bin:${env.PATH}"
    sudo groupadd docker
    sudo usermod -aG docker admin
    chmod 777 /var/run/docker.sock
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


node
{
  stage('Checkout')
  {
    checkout scm
  }
 
  stage('Image build')
  {
    sh "docker build -t ubuntudemo ."
  }

}


pipeline{
  agent any 
  stages{
    stage('CICD'){
      steps{
         sh 'pip install boman-cli '
         sh '~/.local/bin/boman-cli -a run '
      }
    }
  }
}

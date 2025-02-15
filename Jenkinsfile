pipeline { 
  agent any 
  stages {
    stage (cloning git repo) {
      steps{
      git url: 'https://github.com/sharthak0/irctc.git', branch: main
      } 
    } 
    stage (create war file) {
        steps{
          sh 'mvn clean install'
        } 
    } 
  } 
}  
      
      

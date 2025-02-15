pipeline { 
  agent any 
  stages {
    stage (cloning git repo) {
      steps{
      git url: 'https://github.com/sharthak0/irctc.git', brach: main
      } 
    } 
    stage (create war file) {
        steps{
          sh 'mvn clean install'
        } 
    } 
  } 
}  
      
      

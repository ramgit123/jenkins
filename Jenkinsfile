node{
  
    stage('scm check'){
    
  git 'https://github.com/javahometech/my-app'

   }
   
 
  stage('mvn'){
      
      def mvnHome = tool name: 'Maven', type: 'maven'
       
      sh "${mvnHome}/bin/mvn package"
     
  }
   

    }

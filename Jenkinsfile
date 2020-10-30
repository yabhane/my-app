
node { 
   stage('SCM Checkout'){
    // Clone repo	
	//url: 'https://github.com/javahometech/myweb'   
	   git 'https://github.com/yabhane/my-app'
   }
   
   stage('Compile-Package'){
	  sh 'mvn package'
      
   }
	

}


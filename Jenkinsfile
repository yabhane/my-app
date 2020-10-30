
node { 
   stage('SCM Checkout'){
    // Clone repo	
	url: 'https://github.com/javahometech/myweb'   
   }
   
   stage('Compile-Package'){
	  sh 'mvn package'
      
   }
	

}


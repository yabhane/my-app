
node { 
   stage('SCM Checkout'){
    // Clone repo	
	//url: 'https://github.com/javahometech/myweb'   
	  
	   git 'https://github.com/yabhane/my-app'
   }
   
   stage('Compile-Package'){
	   //Get Maven home path
	  def mvnHome = tool name: 'Maven3', type: 'maven'
	   sh "${mvnHome}/bin/mvn package"
      
   }
	

}



node { 
   stage('SCM Checkout'){
    // Clone repo	
	//url: 'https://github.com/javahometech/myweb'   
	  
	   git 'https://github.com/yabhane/my-app'
   }
   
   stage('Compile-Package'){
	   //Get Maven home directory path
	  def mvnHome = tool name: 'Maven3', type: 'maven'
	   //Using this path we are given path to mvn command
	   sh "${mvnHome}/bin/mvn package"
      	 //Output : Created packages in war file
   }
	

}


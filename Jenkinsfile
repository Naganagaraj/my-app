
node {
   // This is to demo github action	
  // def sonarUrl = 'sonar.host.url=http://172.31.30.136:9000'
   //def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn'
   stage('SCM Checkout'){
	  git 'https://github.com/Naganagaraj/my-app'
   }
	
	stage('com,pile-Package'){
	sh 'svn package'	
	}
	
}
    // Clone repo
//	git branch: 'master', 
//	credentialsId: 'github', 
//	url: 'https://github.com/Naganagaraj/my-app'
  // 
   //}
   
 

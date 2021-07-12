node{
    
    stage("Main branch"){	
	      if((env.Branch_Name =~ '.*main.*')) {
		  echo 'This is the main branch'
		 }
       }
    stage("dev branch"){	
	      if((env.Branch_Name =~ '.*dev.*')) {
		  echo 'This is the dev branch and commits in dev branch'
		 }
       }
}

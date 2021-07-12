node{
    
    stage("Main branch"){	
	      if((env.Branch_Name =~ '.*main.*|.*releasefix.*|.*hotfix.*|.*bugfix.*')) {
		  echo 'This is the main branch'
		 }
       }
    stage("dev branch"){	
	      if((env.Branch_Name =~ '.*dev.*|.*releasefix.*|.*hotfix.*|.*bugfix.*')) {
		  echo 'This is the dev branch'
		 }
       }
}	   

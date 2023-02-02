pipeline{
	agent {
		label{
		    label "qa"
		    customWorkspace "/mnt/projects"
			
			}
		}
	stages {
		stage ("stage-1"){
			steps{
			   sleep 10
			   echo "maktej"
				 }
			           }
					   
		stage ("parallel-stage") {
		  parallel {
		     stage ("stage-2") {
			 steps {
		       
				echo "tej"
				  }
				  }
		                  
		stage ("stage-3") {
		    steps {
		        echo "mak"		        
				  }
		                  }
						  }
}						  
	
	
			}
			}


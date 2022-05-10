pipeline 
{
	  agent { label 'slave' }
	  stages 
	  {
		    stage('Build') 
		    {
			      steps 
			      {

				        sh 'echo test'
				        sh '''
				            echo "multi line"
				        ls -lrt
			          '''
			       }
		     }
	    }
 }

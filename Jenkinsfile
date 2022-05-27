pipeline
{
     agent 
	{
	   node
	     {
		label 'built-in'
       	     }
	}
	stages
	  {
	    stage ('1')
             {
		     steps
		     {
		       dir("/project/")
		        {
	                 sh "docker build -t pravin ."
				sh "docker run -itdp 90:8080 pravin"
	                }
		     }
		
	     }
	}
}
  

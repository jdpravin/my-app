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
		       dir("/mnt/project/")
		        {
	                
				sh "docker run -itdp 80:80 httpd"
				
	                }
		     }
		
	     }
	}
}
  

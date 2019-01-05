pipeline
{
	agent 'master'
	stages
	{
	 
	 stage("Code Checkout")
	 {
	 	agent { label 'master' }
	 	steps{
	 			sh 'echo S1'
	 		}
	 }
	 stage("Build")
	 {
	 	agent { label 'master' }
	 	steps 
	 	{
	 		sh 'echo S2'
	 	}
	 }
	 stage("Test")
	 {
	 	agent { label 'master' }
	 	steps 
	 	{
	 		echo 'S3'
	 	}
	 }	

	}
}

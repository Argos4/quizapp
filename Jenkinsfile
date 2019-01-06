def GIT_URL="https://github.com/Argos4/quizapp.git"
def GIT_BRANCH="*/master"
pipeline
{
	
	agent none
	stages
	{
	 
	 stage("Code Checkout")
	 {
	   
	 	agent { label 'master' }
	 	steps{
	 	        
	 			checkout([$class: 'GitSCM', branches: [[name: "${GIT_BRANCH}"]], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: "${GIT_URL}"]]])

	 			//echo """${odyssey_link}${name}"""
	 			
	 			
	 			//sh """
	 			//echo "${name}"
	 			
	 			//"""
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
	

	}
}

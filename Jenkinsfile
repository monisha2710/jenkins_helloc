pipeline{
	agent any
	stages{
		stage("build_makefile"){
			steps{	
				dir("build"){
					bat 'cmake -G "MinGW Makefiles" ..'
					}
			}
			
		}
	}
}

pipeline{
	agent any
	stages{
		stage("build_makefile"){
			steps{	
				cd build
				cmake -G "MinGW Makefiles" ..
			}
			
		}
	}
}

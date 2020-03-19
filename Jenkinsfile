pipeline{
	agent any
	stages{
		stage("build_makefile"){
			cd build
			cmake -G "MinGW Makefiles" ..
			
		}
	}
}

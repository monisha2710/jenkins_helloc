pipeline{
	agent any
	environment{
		PATH = "C:\\WINDOWS\\SYSTEM32;C:\\Program Files (x86)\\CodeBlocks\\MinGW\\bin;C:\\Program Files\\CMake\\bin"
	}
	stages{
		stage("build_makefile"){
			steps{	
				dir("build"){
					bat 'cmake -G "MinGW Makefiles" ..'
					}
			}	
		}
		
		stage("build_exe"){
			steps{
				bat 'cd build'
				bat 'MinGW32-make'
			}
		}
		
		stage("run"){
			steps{
				bat 'hello_1'
			}
		}
	}
}

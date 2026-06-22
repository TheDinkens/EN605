pipeline{
	agent any 
 
	stages{
		stage("compile"){
			steps{
				sh(g++ hello_world.cpp -o test)
			}	

		}
		stage("run"){
			steps{
				sh("./test")
			}
		}

	}

}

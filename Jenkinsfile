pipeline{
 tools{
        jdk 'JAVA_HOME'
        maven 'M2_HOME'
    }
     agent any
	  
	  stages{
	  
	  stage("checkout"){
	   steps{
	   githttps://github.com/Dibyanibariki2022/project.git
	   }
	                  }
	
	   stage("compile"){
	    steps{
		    echo "test"
		 sh 'mvn compile'
		}
		}
		stage("test"){
	    steps{
		 sh 'mvn test'
		}
		}
		stage("package"){
	    steps{
		 sh 'mvn package'
		}
		}
		stage("deploy"){
	    steps{
		 echo "please deploy my application"
		}
		}
		
	  }
	}

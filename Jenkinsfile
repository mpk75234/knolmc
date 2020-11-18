pipeline {
	agent any
	  stages {
	    stage("Stage 1") {
	      steps {
		echo "Hello from KNOLMC #FTW!!!"
		  script {
			rspec `pwd`/spec/basic_spec.rb
				}
			}
		}
	}
}

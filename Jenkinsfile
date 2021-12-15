// //scripted method
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Integration Test') {
// 		echo "Integration Test"
// 	}
// }


//declarative method

pipeline {
	agent any
	stages {
		stage("Build"){
			steps {
				echo "Build"
				echo "Test"
				echo "Integration Test"
			}
		}
		stage("Test"){
			steps {
				echo "Test"
			}
		}
		stage("Integration Test"){
			steps {
				echo "Integration Test"
			}
		}
	}
}
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout'
		ls -lart 	
            }
        }

	stage('Lint') {
            steps {
                echo 'Lint' 
		ls -lart
            }
        }
	stage('Test') {
            steps {
                echo 'Test'
		ls -lart
            }
        }
	stage('Build') {
            steps {
                echo 'Build'
		ls -lart	 
            }
        }
	stage('Delivery') {
            steps {
                echo 'Delivery'
		ls -lart	 
            }
        }
	stage('Deploy') {
            steps {
                echo 'Deploy'
		ls -lart	 
            }
        }
	stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL} with name ${env.JOB_NAME} on branch ${env.BRANCH_NAME}, executer ${env.EXECUTOR_NUMBER}"
		echo "testing jenkins with github"
		echo "testing jenkins with github, ja ja ja !!!!"
		ls -lart	 

            }
        }
    }
}

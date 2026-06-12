pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout'
		checkout scm
		sh 'ls -lart' 	
            }
        }

	stage('Lint') {
            steps {
                echo 'Lint' 
		sh 'ls -lart' 	
            }
        }
	stage('Test') {
            steps {
                echo 'Test'
		sh 'ls -lart'
		sh './helloworld' 	 	
            }
        }
	stage('Build') {
            steps {
                echo 'Build' 
		sh 'gcc -o helloworld helloworld.c'
		sh 'ls -lart' 	
            }
        }
	stage('Delivery') {
            steps {
                echo 'Delivery'
		sh 'ls -lart' 	
		archiveArtifacts artifacts: 'helloworld', fingerprint: true			
            }
        }
	stage('Deploy') {
            steps {
                echo 'Deploy'
		sh 'ls -lart' 	
            }
        }
	stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL} with name ${env.JOB_NAME} on branch ${env.BRANCH_NAME}, executer ${env.EXECUTOR_NUMBER}"
		echo "testing jenkins with github"
		echo "testing jenkins with github, ja ja ja !!!!"
		sh 'ls -lart' 	

            }
        }
    }
}

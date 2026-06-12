pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout'
            }
        }

	stage('Lint') {
            steps {
                echo 'Lint' 
            }
        }
	stage('Test') {
            steps {
                echo 'Test'
            }
        }
	stage('Build') {
            steps {
                echo 'Test'
            }
        }
	stage('Delivery') {
            steps {
                echo 'Delivery'
            }
        }
	stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
	stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL} with name ${env.JOB_NAME} on branch ${env.BRANCH_NAME}, executer ${env.EXECUTOR_NUMBER}"
		echo "testting jenkins with github"
            }
        }
    }
}

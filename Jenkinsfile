pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi') {
            steps {
                echo 'Hi World'
            }
        }
        stage('Good') {
            steps {
                echo 'good World'
            }
        }
    }
	post
	{
	
	always 
	{emailext body: 'Hello this is from jenkins .', subject: 'TestPipeline-jenkins ', to: 'sabuj@commlinkinfotech.com'}
	
	}
}

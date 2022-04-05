pipeline {
    agent any
    stages {
        stage ('build') {
	    steps{
		echo "Hello1"
            }
        }
        stage ('test: integration-&-quality') {
            steps{
                echo "Hello2"
            }
        }
        stage ('test: functional') {
            steps{
                echo "Hello3"
            }
        }
        stage ('test: load-&-security') {
            steps{
                echo "Hello4"
            }
        }
        stage ('approval') {
            steps{
                echo "Hello5"
            }
        }
        stage ('deploy:prod') {
            steps{
                echo "Hello6"
            }
        }
    }
}

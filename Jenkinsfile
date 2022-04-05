pipeline {
    agent any
    stages {
        stage ('build') {
            echo "1"
        }
        stage ('test: integration-&-quality') {
            echo "2"
        }
        stage ('test: functional') {
            echo "3"
        }
        stage ('test: load-&-security') {
            echo "4"
        }
        stage ('approval') {
            echo "5"
        }
        stage ('deploy:prod') {
            echo "6"
        }
    }
}

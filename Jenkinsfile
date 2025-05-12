pipeline {
    agent { 
        node {
            label 'docker-agent'
        }
    }
    triggers {
        pollSCM '*/5 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "Building from Jenkins file"
                echo "By Tathireddy Meghana Reddy- se22ucse268"
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "Testing the build triggered from Jenkins file."
                echo "By Tathireddy Meghana Reddy- se22ucse268"
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                echo "By Tathireddy Meghana Reddy- se22ucse268"
                '''
            }
        }
    }
}

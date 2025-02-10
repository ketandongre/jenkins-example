pipeline {
    agent {
        docker {
            image 'python:3.13.2-alpine3.21'
            args '-v /c/Users/Ketan/.jenkins/workspace/github-jenkins-test_jenkins_test:/workspace -w /workspace'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
pipeline {
    agent any
    stages {
        stage('Use Credentials') {
            steps {
                withCredentials([usernamePassword(credentialsId: '93b560fd-364a-4a24-a7ff-dc95fbcdbbd1', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')]) {
                    sh '''
                        echo "Username: $USERNAME"
                        echo "Password: $PASSWORD"
                    '''
                }
            }
        }
    }
}
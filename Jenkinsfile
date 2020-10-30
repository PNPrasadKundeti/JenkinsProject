pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello CloudBabies!!!"'
                sh '''
                    echo "Welcome to Jenkins..."
                    echo "This is the new line in jenkins file"
                    ls -lah
                '''
            }
        }
    }
}

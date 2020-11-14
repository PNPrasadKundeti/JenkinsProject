pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello CloudBabies!!!"'
                sh '''
                    echo "Welcome to Jenkins..."
                    echo "This is the new line in jenkins file"
                    echo "This is the 2rd line of jenkins file"
                    ls -lah
                '''
            }
        }
    }
}

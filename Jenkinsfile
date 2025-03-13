pipeline {
    stages {
        stage('Build') {
            steps {
                build "PES2UG22CS213-CCLAB"
                sh 'g++ main/hello.cpp -o output'
            }
        }

        failure {
            echo 'Pipeline failed'
        }
    }
}

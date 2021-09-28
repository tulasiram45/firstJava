pipeline {
    agent { dockerfile true }
    stages {
        stage('DockerExample') {
            steps {
                sh 'node --version'
                sh 'svn --version'
                sh 'uname -a'
            }
        }
    }
}

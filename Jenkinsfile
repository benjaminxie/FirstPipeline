pipeline {
    agent { docker { image 'busybox' } }
    stages {
        stage('build') {
            steps {
                sh 'echo hello'
            }
        }
    }
}
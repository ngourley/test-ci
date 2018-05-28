pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'env'
                sh 'echo "Derp"'
                sh 'git log --merges --oneline'
            }
        }
    }
}

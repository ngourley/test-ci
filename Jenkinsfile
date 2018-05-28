pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'env'
                sh 'echo "Derp"'
                git 'git log master --merges --oneline
            }
        }
    }
}

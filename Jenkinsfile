pipeline {
    agent { docker { image 'demotensor:v1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

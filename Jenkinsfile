pipeline {
    //agent { docker { image 'node:6.3' } }
    agent { label 'test' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}

pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('log info docker') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

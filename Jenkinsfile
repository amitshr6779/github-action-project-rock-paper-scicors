pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('log info of docker') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

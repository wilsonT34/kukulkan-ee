pipeline {
    agent { docker { image 'maven:3.6.3-openjdk-11' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn clean verify'
            }
        }
    }
}
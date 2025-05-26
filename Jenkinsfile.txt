pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                sh 'javac Main.java'
                sh 'java Main'
            }
        }
    }
}

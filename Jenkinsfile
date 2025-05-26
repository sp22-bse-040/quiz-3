pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                bat 'javac Main.java'
                bat 'java Main'
            }
        }
    }
}

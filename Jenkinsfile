pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                echo 'truc'
            }
        }
        stage('Checkout') {
             milestone()
             checkout scm
      }
    }
}

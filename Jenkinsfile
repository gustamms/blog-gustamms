pipeline {
    agent any

    stages {
        stage('HelloWorld') {
            steps {
                withSonarQubeEnv(installationName: 'poc') {
                    sh 'composer install'
                }
            }
        }
    }
}
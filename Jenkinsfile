pipeline {
    agent any

    stages {
        stage('HelloWorld') {
            steps {
                withSonarQubeEnv(installationName: 'poc-jenkins') {
                    echo 'Hello World'
                }
            }
        }
    }
}
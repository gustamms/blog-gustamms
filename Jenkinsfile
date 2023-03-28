pipeline {
    agent any

    stages {
        stage('HelloWorld') {
            steps {
                withSonarQubeEnv(installationName: 'poc') {
                    echo 'Hello World'
                }
            }
        }
    }
}
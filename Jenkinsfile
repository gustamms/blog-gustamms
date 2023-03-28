pipeline {
    agent any

    stages {

        stage('Grum PHP Tests') {
            steps {
                sh './vendor/bin/grumphp run'
            }
        }
    }
}
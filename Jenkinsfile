pipeline {
    agent any

    stages {
        stage('Composer install') {
            steps {
                sh 'composer install'
            }
        }
        stage('GrumPHP verify') {
            steps {
                sh './vendor/bin/grumphp run'
            }
        }
    }
}

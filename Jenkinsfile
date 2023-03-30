pipeline { 
    agent any

    stages {
        stage('Composer install') {
            steps {
                sh 'composer install'
            }
        }
        stage('Unit tests') {
            steps {
                sh './vendor/bin/phpunit'
            }
        }
    }
}

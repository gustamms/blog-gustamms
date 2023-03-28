pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/gustamms/blog-gustamms.git'
                sh 'composer install'
            }
        }

        stage('Grum PHP Tests') {
            steps {
                sh './vendor/bin/grumphp run'
            }
        }
    }
}
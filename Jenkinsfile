pipeline {
    agent any

    stages {
        stage('HelloWorld') {
            steps {
                echo 'Hello World'
            }
        }

        stage('git clone') {
            steps {
                git clone "ssh://git@github.com:gustamms/blog-gustamms.git"
            }
        }
    }
}
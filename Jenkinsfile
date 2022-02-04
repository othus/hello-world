pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/othus/hello-world.git'

            }
        }
        stage('test') {
            sh 'echo "this is a test"'
       }
    }
}


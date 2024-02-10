pipeline {
    agent {
        // Specify the label associated with the configured agent 'Manudocker'
        label 'Manudocker'
    }

    stages {
        stage('Checkout') {
            steps {
                // Example: Checkout code from a Git repository
                git 'https://github.com/manuprasadmukundan/pipe1.git'
            }
        }

        stage('Build and Run Docker Container') {
            steps {
                script {
                   
                }
            }
        }

        
    }

    post {
        success {
            // Cleanup Docker resources after a successful build
            script {
               sh 'echo "code is compelted"'
            }
        }
    }
}

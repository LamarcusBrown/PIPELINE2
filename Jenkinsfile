pipeline {
    agent any

    environment {
        HOST_NAME='Jenkins-centOS'
        MY_NAME='Marc'
    }

    stages { 
        // This displays colors using the 'xterm' ansi color map.
            ansiColor('xterm') {
            // Just some echoes to show the ANSI color.
                sh """
               stage "\u001B[31mI'm Red\u001B[0m Now not"
                """
            }
        }
        stage('Environment Prep') {
            steps {
               sh """
                
                """
            }
        }
        stage('Provisioning Infrastructure') {
            steps {
                sh """
                
                """
            }
        }
        stage('Validating Infrastructure') {
            steps {
                sh """
                
                """
            }
        }
    }
}
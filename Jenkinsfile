pipeline {
    agent any

    environment {
        HOST_NAME='Jenkins-centOS'
        MY_NAME='Marc'
    }
    stages {

        stage('Environment Prep') {
        // This shows a simple build wrapper example, using the AnsiColor plugin.
            // This displays colors using the 'xterm' ansi color map.
            // Just some echoes to show the ANSI color.
            steps {
               ansiColor('xterm') {
               sh """
               echo "\u001B[31mI'm Red\u001B[0m Now not"
                """
                }
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

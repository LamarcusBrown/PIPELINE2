pipeline {
    agent any

    environment {
        HOST_NAME='Jenkins-centOS'
        MY_NAME='Marc'
    }

// This shows a simple build wrapper example, using the AnsiColor plugin.
    node {
    // This displays colors using the 'xterm' ansi color map.
    ansiColor('xterm') {
        // Just some echoes to show the ANSI color.
        stage "\u001B[31mI'm Red\u001B[0m Now not"
        }   
    }

    stages {
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
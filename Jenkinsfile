pipeline{
    agent any

    stages{
        stage('Lint Checks') {
            steps{
            sh '''
           # ~/node_modules/jslint/bin/jslint.js server.js
            echo Link checks
            '''
            }
        }
    }
}


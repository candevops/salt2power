pipeline {
    agent any
    stages {
        stage('build') {
            steps {
             echo 'We are Starting the Testing'
pwsh ( returnStatus: true, script: "&.\analytic_engine.ps1")
            } 
        }
    }
}

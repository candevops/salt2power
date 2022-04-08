pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                powershell script: './analytic_engine.ps1'            
            } 
        }
    }
}

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                PowerShell ("., './analytic_engine.ps1'")            
            } 
        }
    }
}

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                pwsh  ("., './analytic_engine.ps1'")            
            } 
        }
    }
}

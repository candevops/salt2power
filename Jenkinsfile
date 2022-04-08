pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                PowerShell(". '.\\analytic_engine.ps1'")             }
        }
    }
}

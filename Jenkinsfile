pipeline {
    agent any
    stages {
        stage('build') {
            steps {
             echo 'We are Starting the Testing'
sh 'powershell var/lib/jenkins/workspace/salt-power1/analytic_engine.ps1' 
            } 
        }
    }
}

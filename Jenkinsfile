pipeline {
    agent any
    stages {
        stage('build') {
            steps {
             echo 'We are Starting the Testing'
powershell  returnStatus: true, script: """\$ExecutionPolicy='Bypass'; \$ErrorActionPreference='Stop';\$ProgressPreference= 'SilentlyContinue';'C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1 6.6.0 C:\\App\\Aurora analytic_engine\\6.6.0-SNAPSHOT analytic-engine 6.6.0-beta.24 sxs zip MCClientFlagFilesPath=.\\C_MCClientConfig64_20210916.A.DEV%3BMOB_PARAM:mdsx_mode=PRODPL'"""
//powershell  returnStatus: true, script: """C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1 6.6.0 C:\\App\\Aurora analytic_engine\\6.6.0-SNAPSHOT analytic-engine 6.6.0-beta.24 sxs zip MCClientFlagFilesPath=.\\C_MCClientConfig64_20210916.A.DEV%3BMOB_PARAM:mdsx_mode=PRODPL"""
             } 
        }
    }
}

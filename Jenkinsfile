pipeline {
    agent any
    stages {
        stage('build') {
            steps {
             echo 'We are Starting the Testing'
//                 powershell returnStatus: true, script: """C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1 1.2.0-beta G:\\App\\Aurora aurora analytic-engine 6.5.0-beta.24 sxs zip"""
                powershell  returnStatus: true, script: """C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1 1.2.0-beta G:\\App\\Aurora aurora analytic-engine 6.5.0-beta.24 sxs zip"""
 //               powershell  returnStatus: true, script: "\$ExecutionPolicy='Bypass'; \$ErrorActionPreference='Stop';\$ProgressPreference= 'SilentlyContinue';'C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1 1.2.0-beta G:\\App\\Aurora aurora analytic-engine 6.5.0-beta.24 sxs zip'"
                //powershell.exe -NonInteractive $ExecutionPolicy='ByPass' "& 'C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1'"
       //         powershell script: """ ErrorActionPreference = "Stop" $ProgressPreference = "SilentlyContinue"  & .\\scripts\\install_analytic_engine.ps1 test1 test2 tes3 test4 """
//powershell.exe $ExecutionPolicy="bypass" $ErrorActionPreference = "Stop"ProgressPreference= "SilentlyContinue" "& 'C:/MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1' test1 "
             //   powershell.exe  -ExecutionPolicy ByPass "& 'C:/MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1'"
                //Powershell "C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1" $args0 $args1 $args2 $args3 $args4 $args5 $args6
                //powershell(" 'C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1' ") 
              //  powershell   returnStatus: true, script: '''
              //      -ErrorActionPreference = 'Stop'  
              //      C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1 1.2.0-beta G:\\App\\Aurora aurora analytic-engine 6.5.0-beta.24 sxs zip'''
          
 //                powershell script: '''\
//$ErrorActionPreference = "Stop"
//cd "$Env:WORKSPACE\MyDirectory"
//& .\myScript.ps1 -user "$Env:creds_USR" -passw "$Env:creds_PSW"
//'''
            } 
        }
    }
}

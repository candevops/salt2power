pipeline {
    agent any
    stages {
        stage('build') {
            steps {
             echo 'We are Starting the Testing'
                $args0 = "1.2.0-beta"
                $args1 = "G:\\App\\Aurora"
                $args2 = "aurora"
                $args3 = "analytic-engine"
                $args4 = "6.5.0-beta.24"
                $args5 = "sxs"
                $args6 = "zip"
                
                //Powershell "C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1" $args0 $args1 $args2 $args3 $args4 $args5 $args6
                powershell(" 'C:\\MyData\\Workspace_cloud_devops\\1-salt-to-powershell\\analytic_engine.ps1' ") 
            } 
        }
    }
}

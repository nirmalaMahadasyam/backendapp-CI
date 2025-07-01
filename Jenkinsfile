pipeline{
    agent{

        Label 'AGENT-1'
    }
    options {
        timeout(time: 30, unit: 'MINUTES')
        disableConcurrentBuilds()
        ansiColor('xterm')
    }
    parameters{
        booleanParam(name: 'deploy', defaultValue: false, description: 'Toggle this value')
    }
    environment{
        def appVersion = '' //variable declaration
       //nexusUrl = 'http://44.203.27.73:8081/repository/backend/' /* not working*/
      // nexusUrl ='172.31.3.84:8081/' // chage this public  172.31.3.84(old)
       //region = "us-east-1"
        //account_id = "851725509871"
    }
    stages{
        
             stage('Test'){
             steps{
                 sh """
                 echo "this is testing"
                 """
             }
         }
        }
    }

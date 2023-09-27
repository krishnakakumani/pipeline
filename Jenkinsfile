pipeline {
    agent any
    stages {
        stage('Pipeline') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], gitTool: 'Default', submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/krishnakakumani/hello-world.git']]])
                echo 'Hello World from pipeline'
            }
        }
    }
    post { 
        always { 
            echo 'Running after the stages'
        }
    }
}

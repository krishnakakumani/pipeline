pipeline {
    agent any
    stages {
        stage('Pipeline') {
            steps {
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/krishnakakumani/hello-world.git']])
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

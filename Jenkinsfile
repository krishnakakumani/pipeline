pipeline {
    agent any
    stages {
        stage('Pipeline') {
            steps {
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

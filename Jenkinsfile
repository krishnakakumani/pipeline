pipeline {
    agent any
    stages {
        stage('Example') {
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

stages {
    
    stage('develop') {
        steps {
            echo 'develop'
        }
    }
    stage('test') {
        steps {
            echo 'test'
        }
    }
    stage('deploy') {
        steps {
            echo 'deploy'
        }
    }
}

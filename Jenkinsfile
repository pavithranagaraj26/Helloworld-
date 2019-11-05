pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent { docker 'impavithra/apache' } 
            steps {
                echo 'Hello'
                sh 'apache --version'
            }
        }
    }
}

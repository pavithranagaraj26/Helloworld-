node('node') {

    stage('Checkout'){

        checkout scm
       }
    pipeline {
         agent { docker { image 'impavithra/apache' } }
            stages {
                 stage('build') {
                    steps {
                        sh 'php --version'
            }
        }
    }
  }
}

pipeline {
    agent any

        stages {

            stage('Unittest') {
                steps {
                    /* use unittest */
                    script {
                       sh 'python unittest.py'
                    }
                }
            }

        } // END stages

    post {
        failure {
            echo 'Email me'
        }
    } // END POST       

} // END pipeline 

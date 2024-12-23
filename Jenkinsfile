pipeline {
    agent any
    stages {
        stage('Build') {
            steps {

                sh 'echo This is Build'
             }
        }
        stage('Test') {
            steps {
                
                sh 'echo This is test'
            }

         }
        stage('Deploy') {
            steps {

                sh 'echo This is deploy'
            }
        }

    }
    post{
        always{
            echo "This sections run always"
        }
        success{
            echo "This section run when pipeline success"
        }
        failure{
            echo "This section run when pipeline failure"
        }
    }
}
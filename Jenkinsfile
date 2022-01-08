pipeline {
    agent { label 'aws_nodes'}

    stages {
        stage('Init') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
         stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
        
    }
     post { 
        always { 
            echo 'I will always say Hello again!'
        }
        failure { 
            echo 'failure'
        }
        success { 
            echo 'success'
        }
    }
}

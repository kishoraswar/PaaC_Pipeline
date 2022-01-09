pipeline{
    agent{
        label "aws_nodes"
    }
    tools{
        maven 'Maven' 
    }
    stages{
        stage("Test"){
            steps{
                sh "mvn --version"
                echo "========executing A========"
            }  
        }
        stage("Build"){
            steps{
                echo "========executing A========"
            }  
        }
        stage("Deploy"){
            steps{
                echo "========executing A========"
            }  
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}


pipeline{
    agent any
        name "Mayank"
    }
    stages{
        stage("Test"){
            steps{
                echo "========executing Test========"
                sh 'pwd'
                echo "${name}"
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

pipeline{
    agent any
    
    stages{
        stage('checkout'){
            steps{
                echo "******checkout******"
            }
        }
        stage('test'){
            steps{
                echo "******test******"
                sh 'pytest'
            }
        }
    }
}

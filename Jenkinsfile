pipeline{
    agent any
    
    stages{
        stage('checkout'){
            steps{
                echo "******checkout******"
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/pickle-rick2000/jenkins_test.git']]])
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

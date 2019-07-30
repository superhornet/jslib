pipeline{
    agent any
    stages{
        stage("A"){
            steps{
                step{
                    echo "====++++executing A++++===="
                    sh 'java -version'
                }
            }
            post{
                always{
                    echo "====++++always++++===="
                }
                success{
                    echo "====++++A executed succesfully++++===="
                }
                failure{
                    echo "====++++A execution failed++++===="
                }
        
            }
        }
    }
}
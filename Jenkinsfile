pipeline{
    agent any
    stage("A"){
        steps{
            echo "====++++executing A++++===="
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
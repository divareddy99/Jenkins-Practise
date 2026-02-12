pipeline{
    agent any
    
    stages{
        stage ("build"){
            steps{
                echo "build completed"
            }
        }
        stage ("test")
        {
            steps{
                echo "test completed"
            }
        }
        
        
    }
    post{
        success{
            echo "completed success"
        }
        always{
            echo "congrats"
        }
        failure{
            echo "fail"
        }
    }
    
    
}

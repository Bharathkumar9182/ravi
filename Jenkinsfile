pipeline{
    agent any
    stages{
        stage("maven build"){
            when{
                branch "develop"
            }
            steps{
                echo "hello from develop"
            }
        }
        stage("deploy"){
            when{
                branch "master"
            }
            steps{
                echo "hello from master"
            }
        }
        
    }
}

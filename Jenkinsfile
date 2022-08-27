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
        stage("maven build"){
            when{
                branch "master"
            }
            steps{
                echo "hello from master"
            }
        }
        
    }
}

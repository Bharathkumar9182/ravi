pipeline{
    agent any
    stages{
        stage("prod"){
            when{
                branch "master"
            }
            steps{
                echo "hello from master"
            }
        }
        
    }
}

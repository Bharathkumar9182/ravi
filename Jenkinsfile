pipeline{
    agent any
    stages{
        stage("maven build"){
            when{
                branch "develop"
            }
            steps{
                sh "mvn package"
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

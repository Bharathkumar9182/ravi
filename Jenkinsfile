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
        stage("notify"){
            steps{
                script{
                mail bcc: '', body: '''hi team,
todays build is success
jill jill jiga jiga''', cc: 'indukuriaditya98@gmail.com', from: '', replyTo: '', subject: 'build success', to: 'ravidheerajteja57@gmail.com'
                }
            }
        }
    }
}

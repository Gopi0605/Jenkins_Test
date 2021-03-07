    pipeline {
        agent any

        stages {
            stage('Docker') {
                steps {
                 sh "sudo docker build -t nginx:pipe ."
                 sh "sudo docker run -itd --name another-nginx nginx:pipe"
                }

            }
        }
    }

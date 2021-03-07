    pipeline {
        agent any

        stages {
            stage('Docker') {
                steps {
                 sh "sudo docker run -itd -p 8089:80 --name nginx-pipe nginx:latest"
                }

            }
        }
    }

pipeline {
    agent any

    stages {
        stage('Deploy to Server') {
            steps {
                sh 'ssh admin-user@192.168.1.100 "sudo docker cp /var/lib/jenkins/workspace/my-app-pipeline/index.html my-app-webserver:/usr/share/nginx/html/index.html"'
            }
        }
    }
}

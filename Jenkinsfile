pipeline{
    agent any
    stages{
        stage("production"){
            steps{
                sh '''
                      sudo docker compose up -d
                      echo '-------------done------------'
                   '''
            }
        }
    }
}
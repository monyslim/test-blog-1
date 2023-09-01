pipeline{
    agent any
    stages{
        stage("production"){
            steps{
                sh '''
                      begin deployment
                      docker compose up -d
                      echo '-------------done------------'
                   '''
            }
        }
    }
}
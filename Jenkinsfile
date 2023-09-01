pipeline{
    agent any
    stages{
        stage("production"){
            steps{
                sh '''
                      docker compose up -d
                      echo '-------------done------------'
                   '''
            }
        }
    }
}
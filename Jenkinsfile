pipeline{
        agent any
        stages{
            stage('source'){
            steps{
                git 'https://github.com/devopstrainingvenkat/game-of-life.git'
            }
            }
            stage('package'){
            steps{
                sh 'mvn package'
                 }
             }
       }
}    

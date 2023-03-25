pipeline{
    
    agent any

      stages{

        stage('git checkout'){

            steps{
                git branch: 'master', url: 'https://github.com/Prabhakar988/Prabhakar_Git.git'
            }
        }

        stage('UNIT Testing'){

            steps{
                sh 'mvn test'
            }
        }

        
            
        
      }

}
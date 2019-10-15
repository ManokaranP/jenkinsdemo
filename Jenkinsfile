pipeline{
    agent any
        stages{
            stage("Welcome"){
                steps{
                    git credentialsId: 'Git', url: 'https://github.com/ManokaranP/Demo'
                }

            }
            stage("Maven build"){
                steps{
            sh "mvn clean package"
            }
            }
            
            }
   
            
        }
}

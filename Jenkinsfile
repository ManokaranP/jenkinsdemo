pipeline{
    environment{
    PATH="C:\Program Files\apache-maven-3.6.2\bin:$PATH"
    }
    
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

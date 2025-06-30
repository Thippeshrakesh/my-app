pipeline{
    agent any
   tools{
    maven 'maven'
   }
    stages{
        stage("Bild process"){
            steps{ 
                sh 'mvn clean package'
            }
        }
    }
}

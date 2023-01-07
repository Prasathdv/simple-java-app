pipeline{
    agents any
    tools {
         maven 'maven'
        }

    stages{
        stage('Build'){
            steps{
                sh label: 'script', script: 'mvn clean package'    
            }
        }
    }
}
    

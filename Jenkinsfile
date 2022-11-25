pipeline{
    agent any 
    stages {
        stage('Lint Checks') {
            steps {
                script {
                    nodejs.lintChecks()                  // Use script { when you're using groovy based conventions }
                }
            }
        } 
        stage('Code Quality Checks') {
            steps {
                sh "echo SonarChecksInProgress"   

            }
        }     
    }   // end of stages 
}  // end of pipelines



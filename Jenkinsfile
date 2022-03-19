pipeline{
    agent any
   tools {
       maven 'maven'
       jdk 'Java'
   }

    stages{
        stage('clean')
        {
            steps{
                sh 'mvn clean'
            }
        }
    }
}

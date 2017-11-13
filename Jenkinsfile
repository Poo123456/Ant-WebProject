pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'ant'
            }
            }
        stage('Deploy') {
            steps {
                echo 'Deploying'
                sh 'cp C:/Users/saket.i.kumar/.jenkins/workspace/AntGit_Jenkinsfile_Web/dist/SampleAntProject.ear C:/Users/saket.i.kumar/Downloads/Tomcat/apache-tomcat-8.5.23-windows-x64/apache-tomcat-8.5.23/webapps'
                sh 'cd C:/Users/saket.i.kumar/Downloads/Tomcat/apache-tomcat-8.5.23-windows-x64/apache-tomcat-8.5.23/bin/startup'
            }
            }
        
        
        }
}	

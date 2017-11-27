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
 	echo 'Deploying'
 	sh 'cp C:/Users/saket.i.kumar/.jenkins/workspace/AntGit_Jenkinsfile_Web/dist/SampleAntProject.ear C:/Users/saket.i.kumar/Downloads/apache-tomcat-7.0.82/apache-tomcat-7.0.82/webapps'
 	sh 'C:/Users/saket.i.kumar/Downloads/apache-tomcat-7.0.82/apache-tomcat-7.0.82/bin/startup.sh'
 	}
 	}
 

        
        
        
        }
}	

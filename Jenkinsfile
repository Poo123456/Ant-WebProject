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
 	sh 'cp C:/Program Files (x86)/Jenkins/workspace/hello/dist/SampleAntProject.ear C:/Users/pooja.s.guptha/Documents/Tomcat/apache-tomcat-7.0.82/webapps'
 	sh 'C:/Users/pooja.s.guptha/Documents/Tomcat/apache-tomcat-7.0.82/bin/startup.sh'
 	}
 	}
 

        
        
        
        }
}	

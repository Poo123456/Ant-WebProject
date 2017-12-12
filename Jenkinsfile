pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'ant'
                echo 'Built ant'
            }
            }
        stage('Deploy') {
            steps {
                echo 'Deploying'
                echo 'Now executing cp command'
                sh 'cp C:/Program Files (x86)/Jenkins/workspace/hello/dist/SampleAntProject.ear C:/Users/pooja.s.guptha/Documents/Tomcat/apache-tomcat-7.0.82/webapps/'
                echo 'copied'
                echo 'starting with startup.sh'
                sh 'C:/Users/pooja.s.guptha/Documents/Tomcat/apache-tomcat-7.0.82/bin/startup.sh'
                echo 'done startup.sh'
            }
        }      
    }
}

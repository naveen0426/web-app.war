pipeline {
   environment {
       JAVA_HOME = '/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.272.b10-3.el8_3.x86_64/'
   }
   agent {
       node {
           label 'Jenkins-slave'
       }
   }
   stages {
       stage (Git Clone) {
            git url: 'https://github.com/naveen0426/web-app.war.git', branch: 'master'
            
}
       

pipeline {
    agent {
      label 'docker-java'
    }
    tools{
        maven "MAVEN_3.8.8"
    }
    stages {
        stage('deploy') {
            steps {
                dir ('rrrr'){
                    git 'https://github.com/spring-projects/spring-petclinic.git'
                    sh  'mvn package'
                }
                
            }
        }
    }
}

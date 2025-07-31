pipeline{
    agent any
    environment{
        name = 'siva'
    }
     
    stages{
        stage('build'){
            when{
                anyOf {
                    branch 'main'
                    environment name:'name', value:'siva'
                }
            }
            steps{
                echo "build success"
            }
        }
    }
}

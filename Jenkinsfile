pipeline {
    agent{
        node{
            label 'java-build-server'
        }
    }
    tool {NodeJS "NodeJS"}
    stages{
        stage('SCM checkout'){
            steps{
                echo "nothing is there"
            }
        }
        stage('build'){
            steps{
                sh 'npm install'
            }
        }
    }
    
    
}


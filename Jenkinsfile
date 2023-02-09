pipeline {
    agent{
        node{
            label 'java-build-server'
        }
    }
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


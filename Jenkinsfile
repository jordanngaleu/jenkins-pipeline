pipeline {
    agent any
    stages{
        stage('clone'){
            steps{
                sh 'echo "clone"'
                sh 'uname -r'
                sh 'nproc'
            }
        }
    stage('test'){
    steps{
        sh 'echo "test"'
    }
  }
    stage('build') {
    steps{
        sh 'touch text-$BUILD_ID'
    }
    }  
    }
}
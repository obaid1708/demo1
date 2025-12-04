pipeline {
    agent any
    stages {
    stage('clean'){
        steps {
            sh 'mvn clean'
        }
    }
    stage ('compile'){
        steps {
            sh 'mvn compile'
        }
    }
    stage ('Test'){
        steps{
            sh 'mvn test'
        }
    }
    stage ('build'){
        steps{
            sh 'mvn clean install'
        }
    }
    
}
}

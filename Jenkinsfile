pipeline {
    agent {
        label 'master'
    }

    stages {
        stage('Test') {
            steps {
              kubectl apply -f kaniko-git.yaml 
               
            }
        }
    }
}

pipeline {
    agent { node { label 'agent' } }
    stages {
        stage('Build') {
            steps {
                echo "anil kumar"
                error 'error'
            }
        }
        // stage('Test') {
        //     steps {
        //         //
        //     }
        // }
        // stage('Deploy') {
        //     steps {
        //         //
        //     }
        // }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
        success {
            echo 'I will run when the job is success'
        }
        failure {
            echo 'I will run when the job fails'
        }
    }
}
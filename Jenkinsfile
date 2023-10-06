pipeline {
    agent { node { label 'agent' } }
    stages {
        stage('Build') {
            steps {
                echo "anil kumar"
            }
        }
        stage('Installation') {
            steps {
                sh '''
                   sudo -i
                    yum install -y yum-utils
                    yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
                    dnf repolist
                     yum -y install terraform
                     terraform  version

                '''
            }
        }
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
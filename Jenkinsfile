pipeline {
    agent {
        label {
            label "master"
        }            
    }

    stages {
        stage ('Check logs') {
            steps {
                sh "cat /var/lib/jenkins/jobs/$JOB_NAME/builds/$JOB_NUMBER"
            }
        }
    }
}

pipeline {
    agent {
        label {
            label "master"
        }            
    }

    stages {
        stage ('Check logs') {
            steps {
                filterLogs ('ERROR', 2)
            }
        }
    }
}

pipeline {
    agent any
    stages {
        stage('STAGE1:BUILD') {
            steps {
        sh '''
        #!/bin/bash
        echo "this is a script"
        cd /var/lib/jenkins/workspace/job_java
        mvn clean install
        '''
            }
        }
stage('STAGE2') {
            steps {
                echo 'this is test stage'
    }
}}
}

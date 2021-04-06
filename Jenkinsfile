pipeline {
    agent any
    stages {
        stage('STAGE1:BUILD') {
            steps {
        sh '''
        #!/bin/bash
        echo "this is a script"
        git pull https://github.com/varshapy/c_code.git
        cd c_code
        make
        '''
            }
        }
stage('STAGE2') {
            steps {
                echo 'this is test stage'
    }
}}
}

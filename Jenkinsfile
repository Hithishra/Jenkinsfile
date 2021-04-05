pipeline {
        agent any
        stages {
        stage("Build") {
        steps {
        sh '''
        #!/bin/bash
        git clone https://github.com/Hithishra/C-project.git 
        cd /var/lib/jenkins/workspace/C-project
        make '''
        }
        }
}
}

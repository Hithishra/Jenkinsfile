pipeline {
        agent any
        stages {
        stage("Build") {
        steps {
        sh '''
        #!/bin/bash
        cd /var/lib/jenkins/workspace/Pipeline-test/C-project
        git pull https://github.com/Hithishra/C-project.git
        make '''
        }
        }
}
}

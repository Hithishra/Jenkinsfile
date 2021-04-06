pipeline {
        agent any
        stages {
        stage("Build") {
        steps {
        sh '''
        #!/bin/bash
        cd /var/lib/jenkins/workspace/Pipeline-test
        git clone https://github.com/Hithishra/C-project.git
        cd C-project
        make '''
        }
        }
}
}

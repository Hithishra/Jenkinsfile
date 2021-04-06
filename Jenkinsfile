pipeline {
        agent any
        stages {
        stage("Build") {
        steps {
        sh '''
        #!/bin/bash
        set +e
        cd /var/lib/jenkins/workspace/Pipeline-test
       ls C-project
       if [ $? -eq 0 ] ; then
        {
                cd C-project
                git pull https://github.com/Hithishra/C-project.git
        }
        else
        {
                git clone https://github.com/Hithishra/C-project.git
                cd C-project
        }
        fi
        make '''
        }
        }
}
}

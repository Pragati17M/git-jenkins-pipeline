pipeline {
    agent any

    stages {
        stage("Clone Repository") {
            steps {
                git "https://github.com/Pragati17M/git-jenkins-pipeline.git"
            }
        }

        stage("Build") {
            steps {
                sh "./hello.sh"
            }
        }
    }
}

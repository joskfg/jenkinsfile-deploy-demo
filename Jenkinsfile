pipeline {
    stages {
        stage("Deploy to production") {
            when {
                branch "master"
            }

            steps {
                sh "docker-compose up -d"
            }
        }
    }
}

node {
    docker.image('node:14-alpine').withRun('-p 3000:3000') {
        stage('Build') {
            sh 'npm install'
        }
    }
}
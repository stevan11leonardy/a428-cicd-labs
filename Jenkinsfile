node {
    docker.image('node:16-buster-slim').withRun('-p 3000:3000') {
        stage('Build') {
            sh 'sudo apt-get update && sudo apt-get install -y npm'
            sh 'npm install'
        }
    }
}
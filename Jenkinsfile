node {
    docker.image('node:16-buster-slim').withRun('-p 3000:3000 --privileged') {
        stage('Build') {
            sh 'apt-get update && apt-get install -y sudo npm'
            sh 'sudo npm install --unsafe-perm=true'
        }
    }
}
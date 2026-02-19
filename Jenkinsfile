stage('Deploy') {
    steps {
        sh 'docker compose -f /root/timesheet-project/docker-compose.yml down'
        sh 'docker compose -f /root/timesheet-project/docker-compose.yml up -d'
    }
}

# Jenkins in Docker Compose
- Set up Jenkins: `docker-compose up -d`
- Open Jenkins Panel: `http://localhost:8080/`
- Get Init Administrator Password: `docker exec jenkins-server cat /var/jenkins_home/secrets/initialAdminPassword`
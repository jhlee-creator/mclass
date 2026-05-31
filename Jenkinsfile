pipeline {
    agent any
    
    tools {
        maven 'maven 3.9.12'
    }

    stages {
        stage('Git Checkout') {
            steps { // steps: stage 안에서 실행할 실제 명령어
                checkout scm // Jenkins에 연결된 Git 저장소에서 최신 코드 체크 아웃
            }
        }
    }
}

/*    environment {
        DOCKER_IMAGE = "demo-app"
        CONTAINER_NAME = "springboot-container"
        JAR_FILE_NAME = "app.jar"
        PORT = "8081"
        REMOTE_USER = "ec2-user"
        REMOTE_HOST = "43.202.34.166"
        REMOTE_DIR = "/home/ec2-user/deploy"
    }

}
*/
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
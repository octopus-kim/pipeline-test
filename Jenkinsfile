pipeline {
    agent any   // 모든 가용 에이전트나 노드에서 실행

    stages {
        stage('Build') {
            steps {
                echo "==== Building the project ===="
                sh 'echo "Compiling source..."'
                // 실제로는 Gradle, Maven, npm 등 빌드 커맨드 실행 가능
            }
        }
        stage('Test') {
            steps {
                echo "==== Running tests ===="
                sh 'echo "Running unit tests..."'
                // 예: sh 'npm test' or sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo "==== Deploying the app ===="
                sh 'echo "Deploy step: e.g., push container image or copy files"'
            }
        }
    }
}

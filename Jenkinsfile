node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/ritikavesit/SimpleJavaApp.git'
    }
}

    stage('Build') {
        sh 'mvn clean compile'
    }

    stage('Test') {
        sh 'mvn test'
    }

    stage('Package') {
        sh 'mvn package'
    }

    stage('Deploy') {
        echo 'Deployment Successful!'
    }
}

node {
    stage('Clone') {
        git 'https://github.com/ritikavesit/SimpleJavaApp'
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

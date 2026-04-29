node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/ritikavesit/SimpleJavaApp.git'
    }


    stage('Build') {
        bat 'mvn clean compile'
    }

    stage('Test') {
        bat 'mvn test'
    }

    stage('Package') {
        bat 'mvn package'
    }

    stage('Deploy') {
        echo 'Deployment Successful!'
    }
}

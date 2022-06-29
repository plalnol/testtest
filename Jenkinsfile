pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep 45
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sleep 30
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep 22
            }
        }
    }
}
// Script //
node {
    stage('Build') {
        echo 'Building....'
        sleep 54
    }
    stage('Test') {
        echo 'Building....'
        sleep 44
    }
    stage('Deploy') {
        echo 'Deploying....'
        sleep 66
    }
}

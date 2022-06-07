pipeline {

agent any

stages {

stage('checkout') {

steps {

git 'https://github.com/Peketi-Bhanuprathapreddy/olx-user-microservices.git'

}

}

stage('compile') {

steps {

echo 'compiling'

}

}

stage('Run') {

steps {

echo 'Running'

}

}

stage('Test Report using jacoco') {

steps {

echo 'jacoco'

}

}

stage('Building Docker Image') {

steps {

echo 'Building Docker Image'

}

}

}

}

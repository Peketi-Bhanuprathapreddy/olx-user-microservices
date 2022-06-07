pipeline {
agent any
  stages {
  

stage('compile') {
steps {
bat 'mvn clean compile'
}
}
stage('running') {
steps {
bat 'mvn package'
}
}
stage('test report using jacoco') {
steps {
jacoco()
}
}
stage('building docker image') {
steps {
echo 'building docker image'
}
}
}
}

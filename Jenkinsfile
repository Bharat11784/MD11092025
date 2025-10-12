pipeline{

agent any
tools{
maven 'maven'
jdk 'java-11'
}

stages{
stage('git-checkout'){
steps{
 git branch: 'main', url: 'https://github.com/Bharat11784/MD11092025.git'
}
}
stage('compile'){
steps{
sh "mvn compile"
}
}
stage('Build'){
steps{
sh "mvn package"
}
}
}
}

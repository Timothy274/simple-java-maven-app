node{
  stage('SCM Checkout'){
    git 'https://github.com/Timothy274/simple-java-maven-app'
  }
  stage ('Compile-Package'){
    sh 'mvn package'
  }
}

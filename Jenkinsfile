node {
  stage('git checkout'){
    git 'https://github.com/pkvanda/mavenrepo.git'
  }
stage(' maven package') {
  sh "mvn clean package"
  }

}

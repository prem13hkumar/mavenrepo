node {
  stage('git checkout'){
    tool name: 'maven', type: 'maven'
    git 'https://github.com/pkvanda/mavenrepo.git'
  }
stage(' maven package') {
  sh "mvn clean package"
  }

}

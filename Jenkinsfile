node {
  stage('git checkout'){
        git 'https://github.com/pkvanda/mavenrepo.git'
  }
stage(' maven package') {
  def mvnhome = tool name: 'maven', type: 'maven'
  sh "${mvnhome}/bin/mvn package"
  }
}

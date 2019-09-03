node {
  stage('git checkout'){
        git 'https://github.com/pkvanda/mavenrepo.git'
  }
stage(' maven package') {
 // def java = tool name: 'jdk', type: 'jdk'
//  def mvnhome = tool name: 'maven', type: 'maven'
  sh "${java}/bin/ ${mvnhome}/bin/mvn package"
  }
}

node{
  stage('SCM Checkout'){
  git 'https://github.com/MouaadKHELLOU/AgileProjet'
  }
  stage('Compile-Package'){
  def mvnHome = tool name: 'maven-3', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
  }
}

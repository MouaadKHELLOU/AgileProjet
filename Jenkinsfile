node{
  stage('SCM Checkout'){
  git 'https://github.com/MouaadKHELLOU/AgileProjet'
  }
  stage('Compile-Package'){
 // def mvnHome = tool name: '', type: 'maven'
    def mvnHome = tool 'Default'
 // sh "${mvnHome}/bin/mvn package"
  }
}

node{
  stage('SCM Checkout'){
  git 'https://github.com/kserge2001/my-ap.git'
}
  stage('Compile-Package'){
    //Get maven home 
    def mvnHome = tool name: 'M2_HOME', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
  
  }

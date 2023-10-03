node{
  stage('SCM Checkout'){
    //def gitHome = tool name: 'git', type: 'git'
    
    git 'https://github.com/ooje2022/DevopsBasics'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}

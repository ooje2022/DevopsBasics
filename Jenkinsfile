node{
  stage('SCM Checkout'){
    def gitHome = tool name: 'git', type: 'git'
    
    "/usr/bin/${gitHome} https://github.com/ooje2022/DevopsBasics"
  }
  stage('Compile-Package'){
    sh 'mnv package'
  }
}

agent {
def mvn = tool (maven : 'M2-HOME',type:'maven')+'\bin\mvn'
stage('compile stage') {
sh "${mvn} clean compile"
}
stage('package stage') {
sh "${mvn} package"
}
}

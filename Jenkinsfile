node {
def mvn = tool (name : 'M2-HOME',type:'maven')+'/bin/mvn'
stage('git checkout') {
git 'https://github.com/vijaykumarbandi/gitmaven.git'
}
stage('compile stage') {
sh "${mvn} clean compile"
}
stage('package stage') {
sh "${mvn} package"
}
}

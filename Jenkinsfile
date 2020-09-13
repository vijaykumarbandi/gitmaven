pipeline {
agent any
stages {
stage('compile stage') {
steps {
withEnv(MAVEN_HOME : 'M2-Home') {
sh 'mvn complie'
}
}
}
}
}

node() {
    stage("Checkout") {
    deleteDir()
    git "https://github.com/ikoshak/test.git"
    }
    
    stage("Build") {
        sh "echo Building ${BUILD_ID} build"
    }
    
    stage("Testing") {
    sh "echo Testing on ${NODE_NAME}"
    }
    
    stage("Pulling") {
    sh "echo Pulling on registry ..."
    }
}

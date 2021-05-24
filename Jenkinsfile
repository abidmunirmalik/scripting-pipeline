// Scripted Pipeline - single-line comment

node('master') {
    stage('Build') {
        buildFunction()
    }
    stage('Test') {
        testFunction()
    }
    stage('Deploy') {
        deployFunction()
    }
}
// Step functions
def buildFunction() {
    println("Build Stage...")
    dir('scripts') {
        sh "./buildScript.sh"
    }
}

def testFunction() {
    println("Testing....")
}

def deployFunction() {
    println("Deploying....")
}

// Scripted Pipeline - single-line comment

node('vjenkinsslv01 (waops)') {
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

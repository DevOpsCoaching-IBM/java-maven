
@Library('ibm-devops-lib') _
import org.ibm.cio.devops.Utilities
def utils = new Utilities(this)


pipeline {
    agent any
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
               script{
                      utils.mvn '--version'
               }
            }
        }
    }
}
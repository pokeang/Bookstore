pipeline {
  agent {
    any
  }
  triggers { pollSCM('*/5 * * * 1-5') }
  stages {
    stage('print out') {
		steps {
			echo "My branch is: ${env.BRANCH_NAME}"
		}   
    }
  }
}

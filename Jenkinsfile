
node('node') {
    currentBuild.result = "SUCCESS"

       stage('Checkout'){

          checkout scm
       }

       stage('Test'){

         env.NODE_ENV = "test"
       }

       stage('Deploy'){

       }

       stage('Cleanup'){

         echo 'prune and cleanup'
       }

}
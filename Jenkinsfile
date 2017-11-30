
node {
    currentBuild.result = "SUCCESS"

       stage('Checkout'){

          checkout scm
       }

       stage('Test'){
         env.NODE_ENV = "test"
         sh 'node -v'
         sh 'npm -v'
       }

       stage('Deploy'){

       }

       stage('Cleanup'){

         echo 'prune and cleanup'
       }

}
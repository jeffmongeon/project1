node {
 
  try {
    stage ('Source control checkout') {
      checkout scm
    }  

    stage ('Execute') {
      sh "echo 'Some good stuff'"
      sh "ls -la"
    }
 
    stage ('Cleanup') {
      //cleanup

    }
  } 
  catch (error) {
    // something went wrong
    sh "echo 'Something not right'"

  }
}



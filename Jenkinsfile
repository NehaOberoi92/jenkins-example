node {
   def mvnHome
   stage('checkout') { // for display purposes
      // Get some code from a GitHub repository
      BRANCH = scm.getBranches()[0]
      echo $BRANCH
      // Get the Maven tool.
      // ** NOTE: This 'M3' Maven tool must be configured
      // **       in the global configuration.           
      mvnHome = tool 'maven'
   }
  
}

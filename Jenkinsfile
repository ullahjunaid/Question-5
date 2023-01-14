pipeline{
    agent any
    stages{
            
             stage("Shubam's 1st stage"){
             steps{
                    echo  "This is 1st stage "
                }
            }
              stage("Shubam's 2n'd stage"){
                steps{
                    echo  "This is stage will show the build number & build Id"
                    echo "${env.BUILD_NUMBER}"
                    echo "${env.BUILD_ID}"        
                }
            }
            
         }
}
//@Library('my-shared-lib') _

pipeline{

    agent any
        stages{
            stage('Git Checkout'){
                steps{
                    script{
                        git 'https://github.com/srikanth0099/e2e_devops.git'
                    //    gitCheckout(
                    //     branch: 'master',
                    //     url: 'https://github.com/srikanth0099/shared_lib_jenkins.git'
                    //    )
                    }
                }
            }
            stage('unit test maven'){
                steps{
                    script{
                        //mvnTest()
                        sh 'mvn test'
                    }
                }
            }
        }

    
}

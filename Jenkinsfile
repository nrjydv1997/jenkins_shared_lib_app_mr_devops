@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        stage("Git checkout"){
            steps{
                    git branch: 'main', url: 'https://github.com/nrjydv1997/jenkins_shared_lib_app_mr_devops.git'
                  /*  gitCheckout(
                        branch: "main",
                        url: "https://github.com/nrjydv1997/jenkins_shared_lib_app_mr_devops.git"
                    ) */
            }
        }
    }
}
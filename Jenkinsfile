node('hpc') {

    stage('Delegate to build job') {
        build job: '../libgse-ci', parameters: [string(name: 'BRANCH_NAME', value: env.BRANCH_NAME)], propagate: true, wait: true
    }

}

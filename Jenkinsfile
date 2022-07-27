node{
stage ('Starting ART job') {
  build job: 'Run', parameters: [[$class: 'StringParameterValue', name: 'branchName', value: ${GIT_BRANCH}]]
}
}

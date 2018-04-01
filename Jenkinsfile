node {
  stage 'Stage 1'
    echo 'Hello there, shell scripts'
  stage 'Checkout'
    git url: 'git@github.com:getpaydays/paydays-api.git'
  stage 'Build'
    sh './myBuild.sh'
  stage 'Deploy'
    sh './myDeployment.sh'
}

#!/usr/bin/env groovy

node {
  docker.image('hello-world').run()
  
  container ("helm") {
    sh "helm -v"
  }
  
  container ("kubectl") {
    sh "kubectl -v"
  }

    container ("elastic") {
    sh "kubectl -v"
  }
  
}

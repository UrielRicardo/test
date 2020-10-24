#!/usr/bin/env groovy

node {
  docker.image('hello-world').run()
  
  container ("helm") {
    sh "helm -v"
  }

  container ("kali") {
    sh "kali -v"
  }

  container ("elk") {
    sh "elk -v"
  }
  
  container ("kubectl") {
    sh "kubectl -v"
  }
 
  container ( " kubectl " ) {
    sh " kubectl -v "
  }
}

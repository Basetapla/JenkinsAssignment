pipeline {
     environment {
     git_url = "https://github.com/Basetapla/JenkinsAssignment.git"
     git_branch = "main"
   }
   agent {label 'prodServer'}
   stages {
       stage('Pull Source') {
      steps {
        git credentialsId: 'ecf738e3-e417-4026-b1b6-5c143793f69c', branch: "${git_branch}", url: "${git_url}"
      }
     }
   }


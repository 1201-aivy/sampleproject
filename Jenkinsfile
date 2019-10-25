node {
 stage('SCM Checkout'){
      git 'https://github.com/1201-aivy/sampleproject'
 }
 stage('Compile-Package'){
     def mvnHome = tool name: 'maven install', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
   }
 }

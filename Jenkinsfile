pipeline{
   agent any
   stages{
     stage('Fetching the code from remote repo'){
         steps {
          git branch: 'main', url: 'https://github.com/Ashwini16-29/maven-jenkin-integration.git'
           }
       }
     stage('converting source code to executable code'){
        steps{
          build 'maven 2'
        }
      }
     stage('testing phase'){
          steps{
             echo 'this is a testing stage'
         }
       }
     stage('deploy phase'){
         steps{
            echo 'deploy information'
          }
       }
    }
 }

pipeline {
  agent any
  stages {
    stage('Test'){
      steps{
      bat "gradle test" 
      archiveArtifacts 'build/test-results/test/*'
      cucumber 'reports/*.json'
   
      }
      
    }

//     stage('Code Analysis') {
//           steps {
//              withSonarQubeEnv('sonar') {
//               bat 'gradle sonarqube '
//             }

          
//           }
//         }
 
//      stage('Code Quality') {
      
//           steps {
//             def qg = waitForQualityGate()
//               if (qg.status != 'OK') {
//                   error "Pipeline aborted due to quality gate failure: ${qg.status}"
//               }
// //              waitForQualityGate true
             
          
//           }
//         }
//      stage('Publish') {
//       steps {
//         bat 'gradle publish'
//       }
//     }
   
//      stage('Build') {
//      steps {
//         bat'gradle build'
//         bat 'gradle javadoc'
//        archiveArtifacts 'build/libs/*.jar, build/docs/javadoc/*'
//      }
       
       
       
        
//      }
 
}

}
 

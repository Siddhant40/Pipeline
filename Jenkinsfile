// pipeline {
//     agent any
//     stages {
//         stage('Breakfast') {
//             steps {
//                 echo "I'm doing breakfast"
//             }
//         }
//         stage('Workout') {
//             steps {
//                 echo "I'm doing Workout"
//             }
//         }
//         stage('Study') {
//             steps {
//                 echo "I'm doing Study"
//             }
//         }
//         stage('Family Time') {
//             steps {
//                 echo "Spending time with family"
//             }
//         }
//         stage('Play') {
//             steps {
//                 echo "I'm playing"
//             }
//         }
//     }
//     post {
//         always {
//             echo "my day went well"
//         }
//     }
// }
node{
  stage('Build'){
    echo "Building"
  }
  stage('Test'){
    echo "Testing"
  }
  if(currentBuild.result=='SUCCESS'){
  echo "Looks good"
}else{
  echo "Error"
}
}

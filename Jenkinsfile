pipeline{
agent any
tools{
Maven "maven3.8.3"
}
stages{
  stage('CheckOutCode'){
  steps{
  git branch: 'main', credentialsId: '2d09fa55-80ab-4887-98e4-a34bdbca313e', url: 'https://github.com/Shaikfayaz15/k8.git'
} 
}
  stage('Build'){
  steps{
   sh "mvn clean package"
    
}
}
}  //stages closing
} //pipeline closing

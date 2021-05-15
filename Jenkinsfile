pipeline{
agent any
stages{
stage('dev-deploy'){
     when{
     branch "dev"
     }
     steps{
      echo "deploy to dev enironment"
       }
    }
     stage('uat-deploy'){
     when{
     branch "uat"
     }
     steps{
      echo "deploy to uat enironment"
       }
    }
     stage('prod-deploy'){
     when{
     branch "main"
     }
     steps{
      echo "deploy to prod enironment"
       }
    }
  }
}

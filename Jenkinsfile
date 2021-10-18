pipeline {
  agent any
  stages {
    stage("one') {
           steps {
             echo"Hii... This is Balaji from TCS"
           }
           }
   stage("Two") {
     steps {
       input("Do you want to proceed?")
     }
   }
 stage("Three"){
   when{
     not{ branch "Master" }
     steps { echo"Hellow"  }
   }
 }
}
            
            
      

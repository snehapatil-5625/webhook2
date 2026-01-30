pipeline{
   agent{
   
label "slave1"


}

stages{
  stage("stage1"){
    steps{
     //sh "mkdir patil"
     sh "sudo yum install httpd -y"
     sh "sudo cp index.html /var/www/html"
      sh "sudo chmod -R 777 /var/www/html"
    
}
}

}





}

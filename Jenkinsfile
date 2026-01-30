pipeline{
   agent{
   
label "slave1"


}

stages{
  stage("stage1"){
    steps{
     sh "mkdir patil"
     sh "sudo yum install httpd -y"
     sh "sudo chmod -R 777 /var/www/html/index.html"
     sh "sudo cp index.html /var/www/html/index.html"
    
}
}

}





}

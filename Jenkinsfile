pipeline{
   agent{
   
label "slave1"


}

stages{
  stage("stage1"){
    steps{
     sh "mkdir sneha"
     sh "sudo yum install httpd -y"
     sh "cp index.html /var/www/html/index.html"
     sh "chmod -R 777 /var/www/html/index.html"
}
}

}





}

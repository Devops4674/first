pipeline{
 agent any
 environment{
 name1="kalai"
 name2='arasan'
 }
 stages{
 stage('concatenate'){
 
 steps{
 script{
 Name= name1 + name2
 }
 echo " concatenate $Name"
 }
 }
 }
}

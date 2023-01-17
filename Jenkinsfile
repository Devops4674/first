pipeline{
 agent any
 environment{
 name1='Gopi'
 name2='Sandhya'
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

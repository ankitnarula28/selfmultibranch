node('built-in') 
 {
 stage('continuousdownload_loans') 
   {
    
     git branch: 'main', url: 'https://github.com/ankitnarula28/awsmaven.git'
 
     }   

stage('Continuousbuild_loans') 

{

sh 'mvn package'

}

}

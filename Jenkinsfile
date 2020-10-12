node{
 stage{'SCM Checkout'}{
   git 'https://github.com/jayashree010491/website/'
   }
   stage {'Compile-Package'}{
   //get the mvn home path
   def mvnhome = tool name: 'maven', type: 'maven'
   sh "${mvnhome}/bin/mvn package"
   }
   }

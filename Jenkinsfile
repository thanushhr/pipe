pipeline {
  agent any	
  stages {

    stage ('PRINT') {
      steps {
        echo "This is Print stage" 
        sh ''' 
		echo "Hello"
	        exit 0 
	   '''
      }  
    }  
    
    stage ('TEST') {
      steps {
        echo "This is Test stage" 
        sh 'sleep 5; exit 0'
      }  
    }  
    
    stage ('DEPLOY') {
      steps {
        echo "This is Deploy stage" 
        sh 'sleep 5'
      }  
    }  
  } 

}

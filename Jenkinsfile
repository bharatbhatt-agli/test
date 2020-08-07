pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
            bat '''
		echo "cloned DEFULT"
	    '''
         }
      }
      stage('Test') {
         steps {
            bat '''
                dir README.md
                type README.md
            '''
         }
      }
   }
}

pipeline{
	agent any
		stages{
			stage('One') {
				steps {
					echo 'Hi, this is Ashish Pal'
				}

			}
			stage('Two') {
				steps {
					input('Do you want to proceed?')
				}

			}
			
			
}	
}

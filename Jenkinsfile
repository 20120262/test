node {
	checkout scm
	
	docker.withRegistry('https://registry.hub.docker.com','dockerHub'){
		def customImage = docker.build("201202623/test")
		
		customImage.push()
	}
}

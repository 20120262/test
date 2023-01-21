node {
	checkout scm
	
	docker.withRegistry('https://registry.hub.docker.com','dockerHub'){
		def customImage = docker.build("20120262/test")
		
		customImage.push()
	}
}

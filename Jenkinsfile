node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("20120262/simpleweb:1.1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}

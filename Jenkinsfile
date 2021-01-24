node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("abhijeetcse123/test1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}

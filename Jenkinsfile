node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com/', 'pratikraipure') {

        def customImage = docker.build("pratikraipure/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}


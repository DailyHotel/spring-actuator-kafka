library identifier: 'yanolja-pipeline-library', changelog: false

publishComPipeline containers: [
            [
                name: 'openjdk'
            ]
        ], {
    publishMaven script: 'bash mvnw clean deploy -Dproject.version=`git rev-parse HEAD | cut -c1-10`'
}
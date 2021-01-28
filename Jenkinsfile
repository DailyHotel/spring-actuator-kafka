library identifier: 'yanolja-pipeline-library', changelog: false

publishComPipeline {
    publishMaven script: 'bash mvnw clean deploy -Dversion=`git rev-parse HEAD | cut -c1-10`'
}
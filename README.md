# dryj-play
Playground for various things

### Example Maven Module

#### Generate
  * mvn archetype:generate -DgroupId=org.dssnt.play -DartifactId=dssnt-play-helloworld -DarchetypeArtifactId=maven-archetype-quickstart -Dpackage=org.dssnt.play.helloworld

#### Build
  1. cd dssnt-play-helloworld
  2. mvn package

#### Run
  * java -cp target/dssnt-play-helloworld-1.0-SNAPSHOT.jar org.dssnt.play.helloworld.App

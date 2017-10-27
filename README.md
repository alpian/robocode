# Robocode

## Getting started
Run
`java -jar lib/robocode-1.9.2.6-setup.jar`
and accept the default install location

Then run
`./gradlew compileJava`

Then
`./gradlew idea`
to create and idea project

Finally open IntelliJ and open the project

To run robocode:

`~/robocode/robocode.sh`

To add your robot run

`./gradlew jar`

Then in Robocode:
1.  Click on options in the menu, then `Clean robot cache`
1.  Click on Robot in the menu
1.  Import Robot or team
1.  Then choose your jar in build/libs/robocode.jar

## Sharing your robot
Send it to `idda@` via email or push it to the repo.

## Robocode documentation
http://robowiki.net/wiki/Robocode/My_First_Robot

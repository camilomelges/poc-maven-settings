# poc-maven-settings

In settings.xml we have the credentials for servers that will be used in our pom.xml

We need to tell for our maven what settings it have to use, for example, in .mvn folder, for default have the maven.config, soo we just need to override the default value of "-s" to settings.xml in our base folder.

Pay atention on the last tip, in maven we can pass "-s" for define the settings used from maven.

BBQjs Maven repository
===============

How to use it
----------

To use this repository add the following to your Pom:

	<distributionManagement>
		<repository>
			<id>repo</id>
			<url>https://github.com/bbqjs/bbq-maven-repo/raw/master/releases</url>
		</repository>
		<snapshotRepository>
			<id>snapshot-repo</id>
			<url>https://github.com/bbqjs/bbq-maven-repo/raw/master/snapshots</url>
		</snapshotRepository>
	</distributionManagement>

Hopefully at some point we'll make it into Maven Central and this won't be necessary.

How to add to it
-------------

To install items in this repo, assuming you've checked this project out into the same directory as the other BBQjs projects, cd into the trunk directory of the project you wish to add and issue the command:

    mvn -DaltDeploymentRepository=snapshot-repo::default::file:../../bbq-maven-repo/releases clean deploy
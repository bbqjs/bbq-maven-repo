BBQjs Maven repository
======================

N.B.

The latest version of bbq can be found at https://github.com/achingbrain/bbq

This repository is here so your builds will not break, however it will not be here forever so please update your pom files!

The new repo details are:

	<repositories>
		<repository>
			<id>achingbrain-releases</id>
			<url>http://achingbrain.github.com/maven-repo/releases</url>
		</repository>
		<repository>
			<id>achingbrain-snapshots</id>
			<url>http://achingbrain.github.com/maven-repo/snapshots</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</repository>
	</repositories>

and the for the plugin repositories…

	<pluginRepositories>
		<pluginRepository>
			<id>achingbrain-releases</id>
			<url>http://achingbrain.github.com/maven-repo/releases</url>
		</pluginRepository>
		<pluginRepository>
			<id>achingbrain-snapshots</id>
			<url>http://achingbrain.github.com/maven-repo/snapshots</url>
			<snapshots>
				<enabled>true</enabled>
			</snapshots>
		</pluginRepository>
	</pluginRepositories>
To deploy to local directory, use:
mvn -DaltDeploymentRepository=release-repo::default::file:..\xsalefter-maven-repo\releases clean deploy

or
mvn -DaltDeploymentRepository=snapshot-repo::default::file:..\xsalefter-maven-repo\snapshots clean deploy
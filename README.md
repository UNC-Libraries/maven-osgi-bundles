This project repackages a number of workbench dependencies in OSGi bundles. It adds these bundles to a p2 repository site, which can be uploaded to a web server. From there they are included in the Eclipse target of the workbench and incorporated into builds.

You build the P2 site with this Maven command:

    # mvn p2:site

The latest p2 site for workbench dependencies is located here:

http://www2.lib.unc.edu/software/workbench/p2/maven-osgi-bundles

Markdown Maven Site
===================
Test successul!

Congratulations! If you are looking at this page then you have successfully generated a maven site using
the markdown syntax !

You had added the following snippet to your _pom_ file:

    <dependencies>
        <dependency>
            <groupId>org.kohsuke</groupId>
            <artifactId>doxia-module-markdown</artifactId>
            <version>1.0</version>
        </dependency>
    </dependencies>

And you had generated the web site using:

    mvn site

It has generated the web site for ${project.groupId}:${project.artifactId}:${project.version}.

# OME MDB Tools

[![Build Status](https://github.com/ome/ome-mdbtools/workflows/Maven/badge.svg)](https://github.com/ome/ome-mdbtools/actions)
[![Maven Central](https://img.shields.io/maven-central/v/org.openmicroscopy/ome-mdbtools.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.openmicroscopy%22%20AND%20a%3A%22ome-mdbtools%22)
[![Javadocs](http://javadoc.io/badge/org.openmicroscopy/ome-mdbtools.svg)](http://javadoc.io/doc/org.openmicroscopy/ome-mdbtools)

This is a fork of the [mdbtools-java](http://mdbtools.cvs.sourceforge.net/viewvc/mdbtools/mdbtools-java/) project. There are numerous bug fixes, as well as changes to reduce the memory required for large files. There are no dependencies on other components.


More information
----------------

For more information, see the [MDB Tools project on GitHub](https://github.com/mdbtools/mdbtools).


Pull request testing
--------------------

We welcome pull requests from anyone, but ask that you please verify the
following before submitting a pull request:

 * verify that the branch merges cleanly into ```master```
 * verify that the branch compiles using Maven
 * verify that the branch does not use syntax or API specific to Java 1.8+
 * make sure that your commits contain the correct authorship information and,
   if necessary, a signed-off-by line
 * make sure that the commit messages or pull request comment contains
   sufficient information for the reviewer(s) to understand what problem was
   fixed and how to test it

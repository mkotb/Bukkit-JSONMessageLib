JSONChatLib
===========

Empty

Compiling
=========

- Download & Install [Maven 3](http://maven.apache.org/download.html)
- Clone the repository: `git clone https://github.com/mazentheamazin/PrisonRankup`
- Compile and create the plugin package using Maven: `mvn clean install`

Maven will download all required dependencies and build a ready-for-use plugin package!

Adding JSONChatLib as a Maven Dependency
========================================

Adding JSONChatLib as a Maven dependency is easy, lets go over how to do it.

First, add the JSONChatLib repo.

``` xml

<repository>
    <id>jsonchatlib-repo</id>
    <url>https://raw.github.com/mazentheamazin/Bukkit-JSONMessageLib/mvn-repo/</url>
</repository>

```

Now, we just need to add the dependency:

``` xml

<dependency>
    <groupId>io.mazenmc</groupId>
    <artifactId>JSONChatLib</artifactId>
    <scope>compile</scope>
    <version>1.0</version>
</dependency>

```
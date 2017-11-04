# Kotlin Minimal Quickstart

This is a Maven Archetype for starting a minimal Kotlin project. It includes the following:

- Configured to compile against Java 1.8
- Fixes warnings that Maven generates by default

# Usage

To create a new project using this archetype:

```bash
$ mvn archetype:generate -B -DarchetypeGroupId=org.spilth -DarchetypeArtifactId=kotlin-minimal-quickstart -DgroupId=com.example -DartifactId=helloworld -Dversion=1.0.0
$ cd helloworld
$ mvn package
```


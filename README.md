# corenlp-fr-models

## Purpose

This repository repackages the Stanford CoreNLP french models with an added
NER model from [KB Labs](http://lab.kb.nl/dataset/europeana-newspapers-ner#access).

## Packaging

```bash
mvn package install
```

## Pushing to mirror

```bash
mcli mirror ~/.m2/repository/nekonyuu/corenlp-fr-models artifacts/snapshots/maven/nekonyuu/corenlp-fr-models
```

## Use it on your own project


In SBT :
```
resolvers += "GitHub nekonyuu artifacts - snapshots" at "https://artifacts.nyuu.eu/snapshots"
libraryDependencies ++= Seq(
  "nekonyuu" %% "corenlp-fr-models" % "3.9.1-custom"
)
```

In maven :
```
<repositories>
		<repository>
		    <id>GitHub nekonyuu artifacts - snapshots</id>
		    <url>https://artifacts.nyuu.eu/snapshots</url>
		</repository>
</repositories>
```

```
<dependency>
	    <groupId>nekonyuu</groupId>
	    <artifactId>corenlp-fr-models</artifactId>
	    <version>3.9.1-custom</version>
</dependency>
```

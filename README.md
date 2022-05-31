# mule-micorp-pom
> Parent POM file for Micorp Demo Services

## Table of contents
1. [Prerequisites](#prerequisites)
2. [Deployment](#deployment)
3. [Recommended content](#recommended-content)

<br>

## Prerequisites
To compile and build the project:
* Java Development Kit (JDK) 8. Must be version 8!
* Apache Maven, version 3.8 or later.
* IDE, Anypoint Studio or IntelliJ.

Deployment in Anypoint Exchange:
* Anypoint account credentials

<br>

## Deployment

Configure settings.xml in your machine with the correct credentials for Anypoint Platform
```xml
	<servers>
		<server>
			<id>anypoint-exchange-v3</id>
			<username>MY-USER</username>
			<password>MY-PASSWORD</password>
		</server>
	</servers>
```

The <id> must be the same between settings.xml and the repository defined in pom.xml.
Deploy the pom changes to Anypoint platform, from the command line type:

```xml
mvn deploy
```

<br>

## Recommended content
* [How to work with a parent pom](https://help.mulesoft.com/s/article/How-to-work-with-a-parent-pom)
* [How to deploy mule extension with pom hierarchy to exchange](https://help.mulesoft.com/s/article/How-to-deploy-mule-extension-with-pom-hierarchy-to-exchange)

---
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
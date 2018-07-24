# BookManager

## Project Information
This project is the manager of books. I used the MySQL database and JDBC.
In this project implemented standard [CRUD](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) operations:
* Create
* Read
* Update
* Delete

Take a look at the project [PLAN](PLAN.md). All scripts are in the folder [resources/db](src/main/resources/db).

SQL scripts:
* [Init table script](src/main/resources/db/initDBTable.sql)
* [Populate script](src/main/resources/db/populateDB_MySQL.sql)

## Technologies
| Technology     | Badge |
|:--------------:|:-----:|
| License        | [![LICENSE](https://img.shields.io/badge/LICENSE-Apache%202.0-blue.svg)](LICENSE) |
| Travis CI      | [![Build Status](https://travis-ci.org/qThegamEp/BookManager.svg?branch=master)](https://travis-ci.org/qThegamEp/BookManager) |
| AppVeyor CI    | [![Build status](https://ci.appveyor.com/api/projects/status/kqktu8egoaxf36hc?svg=true)](https://ci.appveyor.com/project/qThegamEp/bookmanager) |
| Codecov        | [![codecov](https://codecov.io/gh/qThegamEp/BookManager/branch/master/graph/badge.svg)](https://codecov.io/gh/qThegamEp/BookManager) |
| Codacy         | [![Codacy Badge](https://api.codacy.com/project/badge/Grade/f8c8ec3ea86f4c33bd9ffb2100fcae4d)](https://www.codacy.com/app/qThegamEp/BookManager?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=qThegamEp/BookManager&amp;utm_campaign=Badge_Grade) |
| Gitter         | [![Gitter](https://badges.gitter.im/qThegamEp/BookManager.svg)](https://gitter.im/qThegamEp/BookManager?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) |

## Import Information
If you want to use this project:
1. You have to "*clone*" on your GitHub or "*download*" this project;
2. If you selected to "*download*" the project then start your Intellij IDEA and choose the "*Import Project*" and then choose as "*Maven*" project else if you selected to "*clone*" the project choose the "*Check out from Version Control*" and then choose "*Git*" and and select your repository in which you cloned this project;
3. If your version is Java 10 then you can skip this item otherwise you have to open the "*pom.xml*" file and look for the line `<java.version>1.10</java.version>` and change the value to your version of Java;
4. Run the project;
5. If you want to package a jar file, then open the "*Lifecycle*" of the Maven and choose "*package*";

## Implementation Information
* **Programming Language:** Java
* **Build System:** [Maven](https://maven.apache.org/)
* **Control System:** [Git](https://git-scm.com/)
* **License:** [Apache license, version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
* **Continuous Integration:**
    * [Travis CI](https://travis-ci.org/)
    * [AppVeyor CI](https://ci.appveyor.com)
* **Code Coverage:** [Codecov.io](https://codecov.io/)
* **Code Style:** [Codacy](https://www.codacy.com/)
* **Chat:** [Gitter](https://gitter.im/)
* **Annotations:**
    * [JetBrains Annotations](https://blog.jetbrains.com/dotnet/2018/05/03/what-are-jetbrains-annotations/)
    * [Lombok](https://projectlombok.org/)
* **Automated Testing:**
    * [JUnit4](https://junit.org/junit4/)
    * [AssertJ](http://joel-costigliola.github.io/assertj/)
    * [Mockito](http://site.mockito.org/)
* **Mutation Testing:** [Pitest](http://pitest.org/)
* **Log:**
    * [SLF4J](https://www.slf4j.org/)
    * [Logback](https://logback.qos.ch/)
* **Database:** [MySQL](https://dev.mysql.com/)

## Resources
* **External Libraries:**
	* [JetBrains Annotations](https://mvnrepository.com/artifact/org.jetbrains/annotations)
	* [Lombok](https://mvnrepository.com/artifact/org.projectlombok/lombok)
	* [JUnit4](https://mvnrepository.com/artifact/junit/junit)
	* [AssertJ](https://mvnrepository.com/artifact/org.assertj/assertj-core)
    * [Mockito](https://mvnrepository.com/artifact/org.mockito/mockito-core)
    * [SLF4J API](https://mvnrepository.com/artifact/org.slf4j/slf4j-api)
    * [JCL Over SLF4J](https://mvnrepository.com/artifact/org.slf4j/jcl-over-slf4j)
    * [JUL to SLF4J](https://mvnrepository.com/artifact/org.slf4j/jul-to-slf4j)
    * [Logback](https://mvnrepository.com/artifact/ch.qos.logback/logback-classic)
    * [MySQL JDBC](https://mvnrepository.com/artifact/mysql/mysql-connector-java)
* **Plugins:**
    * [Compiler Plugin](https://maven.apache.org/plugins/maven-compiler-plugin/)
    * [Assembly Plugin](http://maven.apache.org/plugins/maven-assembly-plugin/)
    * [Pitest Plugin](http://pitest.org/quickstart/maven/)
    * [JaCoCo Plugin](http://www.baeldung.com/jacoco)
    * [Versions Maven Plugin](http://www.mojohaus.org/versions-maven-plugin/)

## Contact Information
* **Author:** Koliadin Nikita
* **Facebook:** [My Facebook](https://www.facebook.com/koliadin.nikita)
* **Gmail:** qThegamEp@gmail.com
* **JavaRush:** [My JavaRush](https://javarush.ru/users/1324097)

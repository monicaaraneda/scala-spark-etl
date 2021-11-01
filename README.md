# scala-spark-etl

Project source code for Monica Araneda Lee's Aparch Spark with Scala Challenge.

# Project Spark with IntelliJ IDEA

Data Engineer - Challenge  ETL  scala-spark-etl.jar

Hi, I’m @maranedaex


## Using this project with Apache Spark 2.0 con Scala

$ git clone scala-spark-etl.git

### developer ide mode local

$ cd scala-spark-etl.git
$ ./gradlew idea

## create App self contained

$ cd scala-spark-etl.git
$ ./gradlew jar
$ cp build/libs/Challenge-spark.jar ../../sparkJob/
$ cp data/in/result.csv ../../sparkJob/
$ ./bin/spark-submit Challenge-spark.jar

## Mode Spark submit  

1.- download the spark distribution
2.- download jar file
3.- upload jar file to spark cluster


## Result from TopGames provided 

=== The 10 best games for each console/company. of SONY ===
+-------+-------+--------------+. 
|company|console|max(metascore)| 
+-------+-------+--------------+. 
|   SONY|    PS4|            97|. 
|   SONY|    PS3|            98| 
|   SONY|    PS2|            97| 
|   SONY|    PSP|            91| 
|   SONY|   VITA|            93| 
|   SONY|     PS|            98| 
+-------+-------+--------------+ 

=== The 10 best games for each console/company. of MICROSOFT ===
+---------+-------+--------------+
|  company|console|max(metascore)|
+---------+-------+--------------+
|MICROSOFT|   XONE|            98|
|MICROSOFT|   X360|            98|
|MICROSOFT|   XBOX|            97|
+---------+-------+--------------+

=== The 10 best games for each console/company. of NINTENDO ===
+--------+-------+--------------+
| company|console|max(metascore)|
+--------+-------+--------------+
|NINTENDO| Switch|            97|
|NINTENDO|     DS|            93|
|NINTENDO|     GC|            97|
|NINTENDO|    N64|            97|
|NINTENDO|    WII|            97|
|NINTENDO|    GBA|            95|
|NINTENDO|    3DS|            94|
|NINTENDO|   WIIU|            96|
+--------+-------+--------------+

=== The 10 best games for each console/company. of SEGA ===
+-------+-------+--------------+
|company|console|max(metascore)|
+-------+-------+--------------+
|   SEGA|     DC|            97|
+-------+-------+--------------+

=== The 10 best games for each console/company. of PC ===
+-------+-------+--------------+
|company|console|max(metascore)|
+-------+-------+--------------+
|     PC|     PC|            96|
+-------+-------+--------------+

=== The 10 best games for each console/company. of SONY ===
+-------+-------+--------------+
|company|console|min(metascore)|
+-------+-------+--------------+
|   SONY|    PS4|            21|
|   SONY|    PS3|            17|
|   SONY|    PS2|            24|
|   SONY|    PSP|            28|
|   SONY|   VITA|            33|
|   SONY|     PS|            25|
+-------+-------+--------------+

=== The 10 best games for each console/company. of MICROSOFT ===
+---------+-------+--------------+
|  company|console|min(metascore)|
+---------+-------+--------------+
|MICROSOFT|   XONE|            23|
|MICROSOFT|   X360|            17|
|MICROSOFT|   XBOX|            22|
+---------+-------+--------------+

=== The 10 best games for each console/company. of NINTENDO ===
+--------+-------+--------------+
| company|console|min(metascore)|
+--------+-------+--------------+
|NINTENDO| Switch|            17|
|NINTENDO|     DS|            20|
|NINTENDO|     GC|            23|
|NINTENDO|    N64|            41|
|NINTENDO|    WII|            18|
|NINTENDO|    GBA|            24|
|NINTENDO|    3DS|            26|
|NINTENDO|   WIIU|            11|
+--------+-------+--------------+

=== The 10 best games for each console/company. of SEGA ===
+-------+-------+--------------+
|company|console|min(metascore)|
+-------+-------+--------------+
|   SEGA|     DC|            38|
+-------+-------+--------------+

=== The 10 best games for each console/company. of PC ===
+-------+-------+--------------+
|company|console|min(metascore)|
+-------+-------+--------------+
|     PC|     PC|            16|
+-------+-------+--------------+

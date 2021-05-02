# Scala spark wordcount app 
- Created with gradle init
- In Gradle 7.0 file structure will be multi project format, with
  a scala application in a subdirectory called app
- build.gradle files will exist in subdirectories but not in root directory
- Ensure that scala library dependency version matches the scala version of the target spark cluster or spark-submit will fail on a ClassNotFoundException.

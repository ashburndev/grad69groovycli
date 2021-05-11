# grad69groovycli

```
https://gradle.org/install/
https://gradle.org/install/#manually
https://gradle.org/releases/

https://docs.gradle.org/current/userguide/groovy_plugin.html
https://docs.gradle.org/current/userguide/tutorial_using_tasks.html
https://docs.gradle.org/current/samples/sample_building_groovy_applications.html

05/02/2021  01:39 PM        25,460,838 micronaut-cli-2.5.0.zip
05/02/2021  01:51 PM         4,923,928 grails-4.0.10-docs.zip
05/11/2021  06:31 AM       108,129,558 gradle-6.9-bin.zip
05/11/2021  06:31 AM                64 gradle-6.9-bin.zip.sha256
05/11/2021  06:33 AM       150,849,355 gradle-6.9-all.zip
05/11/2021  06:33 AM                64 gradle-6.9-all.zip.sha256
05/11/2021  06:33 AM       112,062,196 gradle-7.0.1-bin.zip
05/11/2021  06:33 AM                64 gradle-7.0.1-bin.zip.sha256
05/11/2021  06:33 AM       154,338,174 gradle-7.0.1-all.zip
05/11/2021  06:33 AM                64 gradle-7.0.1-all.zip.sha256
05/11/2021  06:38 AM        80,042,000 VSCodeUserSetup-x64-1.56.0.exe
05/11/2021  06:39 AM        80,041,848 VSCodeSetup-x64-1.56.0.exe
05/11/2021  06:39 AM       111,114,416 VSCode-win32-x64-1.56.0.zip
            1509 File(s) 225,970,980,144 bytes
              29 Dir(s)   7,919,624,192 bytes free

C:\Users\David Holberton\Downloads>certutil -hashfile gradle-6.9-bin.zip SHA256
SHA256 hash of gradle-6.9-bin.zip:
765442b8069c6bee2ea70713861c027587591c6b1df2c857a23361512560894e
765442b8069c6bee2ea70713861c027587591c6b1df2c857a23361512560894e
CertUtil: -hashfile command completed successfully.

C:\Users\David Holberton\Downloads>certutil -hashfile gradle-6.9-all.zip SHA256
SHA256 hash of gradle-6.9-all.zip:
5d234488d2cac2ed556dc3c47096e189ad76a63cf304ebf124f756498922cf16
5d234488d2cac2ed556dc3c47096e189ad76a63cf304ebf124f756498922cf16
CertUtil: -hashfile command completed successfully.

C:\Users\David Holberton\Downloads>certutil -hashfile gradle-7.0.1-bin.zip SHA256
SHA256 hash of gradle-7.0.1-bin.zip:
dccda8aa069563c8ba2f6cdfd0777df0e34a5b4d15138ca8b9757e94f4e8a8cb
dccda8aa069563c8ba2f6cdfd0777df0e34a5b4d15138ca8b9757e94f4e8a8cb
CertUtil: -hashfile command completed successfully.

C:\Users\David Holberton\Downloads>certutil -hashfile gradle-7.0.1-all.zip SHA256
SHA256 hash of gradle-7.0.1-all.zip:
ca42877db3519b667cd531c414be517b294b0467059d401e7133f0e55b9bf265
ca42877db3519b667cd531c414be517b294b0467059d401e7133f0e55b9bf265
CertUtil: -hashfile command completed successfully.

C:\Users\David Holberton\Downloads>type gradle-6.9-bin.zip.sha256
765442b8069c6bee2ea70713861c027587591c6b1df2c857a23361512560894e
C:\Users\David Holberton\Downloads>
C:\Users\David Holberton\Downloads>type gradle-6.9-all.zip.sha256
5d234488d2cac2ed556dc3c47096e189ad76a63cf304ebf124f756498922cf16
C:\Users\David Holberton\Downloads>
C:\Users\David Holberton\Downloads>type gradle-7.0.1-bin.zip.sha256
dccda8aa069563c8ba2f6cdfd0777df0e34a5b4d15138ca8b9757e94f4e8a8cb
C:\Users\David Holberton\Downloads>
C:\Users\David Holberton\Downloads>type gradle-7.0.1-all.zip.sha256
ca42877db3519b667cd531c414be517b294b0467059d401e7133f0e55b9bf265
C:\Users\David Holberton\Downloads>


Microsoft Windows [Version 10.0.19042.928]
(c) Microsoft Corporation. All rights reserved.

C:\Users\David Holberton>gradle --version

Welcome to Gradle 6.9!

Here are the highlights of this release:
 - This is a small backport release.
 - Java 16 can be used to compile when used with Java toolchains
 - Dynamic versions can be used within plugin declarations
 - Native support for Apple Silicon processors

For more details see https://docs.gradle.org/6.9/release-notes.html


------------------------------------------------------------
Gradle 6.9
------------------------------------------------------------

Build time:   2021-05-07 07:28:53 UTC
Revision:     afe2e24ababc7b0213ccffff44970aa18035fc0e

Kotlin:       1.4.20
Groovy:       2.5.12
Ant:          Apache Ant(TM) version 1.10.9 compiled on September 27 2020
JVM:          11.0.10 (Oracle Corporation 11.0.10+8-LTS-162)
OS:           Windows 10 10.0 amd64

C:\Users\David Holberton>java -version
java version "11.0.10" 2021-01-19 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.10+8-LTS-162)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.10+8-LTS-162, mixed mode)

C:\Users\David Holberton>groovy --version
Groovy Version: 3.0.7 JVM: 11.0.10 Vendor: Oracle Corporation OS: Windows 10

C:\Users\David Holberton>mvn -v
Apache Maven 3.6.0 (97c98ec64a1fdfee7767ce5ffb20918da4f719f3; 2018-10-24T14:41:47-04:00)
Maven home: C:\LocalApps\apache-maven-3.6.0\bin\..
Java version: 11.0.10, vendor: Oracle Corporation, runtime: C:\LocalApps\Java\jdk-11.0.10
Default locale: en_US, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

C:\Users\David Holberton>

C:\Users\David Holberton\grad69groovycli>
C:\Users\David Holberton\grad69groovycli>dir /o:gd
 Volume in drive C has no label.
 Volume Serial Number is 4603-A8D3

 Directory of C:\Users\David Holberton\grad69groovycli

05/11/2021  07:19 AM    <DIR>          .gradle
05/11/2021  07:19 AM    <DIR>          gradle
05/11/2021  07:19 AM    <DIR>          ..
05/11/2021  07:19 AM    <DIR>          .
05/11/2021  07:19 AM    <DIR>          app
05/11/2021  07:19 AM             5,766 gradlew
05/11/2021  07:19 AM             2,763 gradlew.bat
05/11/2021  07:19 AM               388 settings.gradle
05/11/2021  07:19 AM               108 .gitignore
05/11/2021  07:19 AM               160 .gitattributes
               5 File(s)          9,185 bytes
               5 Dir(s)  25,154,691,072 bytes free

C:\Users\David Holberton\grad69groovycli>tree /a
Folder PATH listing
Volume serial number is 4603-A8D3
C:.
+---.gradle
|   +---6.9
|   |   +---executionHistory
|   |   +---fileChanges
|   |   +---fileHashes
|   |   \---vcsMetadata-1
|   +---buildOutputCleanup
|   +---checksums
|   \---vcs-1
+---app
|   \---src
|       +---main
|       |   +---groovy
|       |   |   \---grad69groovycli
|       |   \---resources
|       \---test
|           +---groovy
|           |   \---grad69groovycli
|           \---resources
\---gradle
    \---wrapper

C:\Users\David Holberton\grad69groovycli>
C:\Users\David Holberton\grad69groovycli>.\gradlew run
Downloading https://services.gradle.org/distributions/gradle-6.9-bin.zip
..........10%..........20%..........30%...........40%..........50%..........60%...........70%..........80%..........90%...........100%

> Task :app:run
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.codehaus.groovy.reflection.CachedClass (file:/C:/Users/David%20Holberton/.gradle/caches/modules-2/files-2.1/org.codehaus.groovy/groovy/2.5.13/ac054525fdc81cbd0bc2552b57052ebb1a93cd40/groovy-2.5.13.jar) to method java.lang.Object.finalize()
WARNING: Please consider reporting this to the maintainers of org.codehaus.groovy.reflection.CachedClass
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
Hello World!

BUILD SUCCESSFUL in 13s
2 actionable tasks: 2 executed
C:\Users\David Holberton\grad69groovycli>
C:\Users\David Holberton\grad69groovycli>.\gradlew build

> Task :app:test
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.codehaus.groovy.reflection.CachedClass (file:/C:/Users/David%20Holberton/.gradle/caches/modules-2/files-2.1/org.codehaus.groovy/groovy/2.5.13/ac054525fdc81cbd0bc2552b57052ebb1a93cd40/groovy-2.5.13.jar) to method java.lang.Object.finalize()
WARNING: Please consider reporting this to the maintainers of org.codehaus.groovy.reflection.CachedClass
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release

BUILD SUCCESSFUL in 6s
7 actionable tasks: 6 executed, 1 up-to-date
C:\Users\David Holberton\grad69groovycli>
C:\Users\David Holberton\grad69groovycli>dir app\build\distributions
 Volume in drive C has no label.
 Volume Serial Number is 4603-A8D3

 Directory of C:\Users\David Holberton\grad69groovycli\app\build\distributions

05/11/2021  07:26 AM    <DIR>          .
05/11/2021  07:26 AM    <DIR>          ..
05/11/2021  07:26 AM        16,916,480 app.tar
05/11/2021  07:26 AM        15,099,849 app.zip
               2 File(s)     32,016,329 bytes
               2 Dir(s)  24,884,011,008 bytes free

C:\Users\David Holberton\grad69groovycli>
C:\Users\David Holberton\grad69groovycli>
C:\Users\David Holberton\grad69groovycli>jar tvf app\build\distributions\app.tar
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/
   501 Sun Apr 07 19:28:14 EDT 2019 META-INF/MANIFEST.MF
     0 Sun Apr 07 19:28:06 EDT 2019 org/
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/
   887 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/JUnitException.class
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/
  5145 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/PackageUtils.class
  2550 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ToStringBuilder.class
 15001 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ClasspathScanner.class
   960 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/PreconditionViolationException.class
  3107 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ClassUtils.class
  5232 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/StringUtils.class
  4283 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ClassFileVisitor.class
  3338 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ModuleUtils.class
  3330 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ClassFilter.class
  2287 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/FunctionUtils.class
 48004 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ReflectionUtils.class
  5069 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/CollectionUtils.class
  5788 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/Preconditions.class
  4340 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/CloseablePath.class
  1793 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ExceptionUtils.class
  1359 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ReflectionUtils$HierarchyTraversalMode.class
 14351 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/AnnotationUtils.class
  2201 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/BlacklistedExceptions.class
  2759 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/util/ClassLoaderUtils.class
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/annotation/
   714 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/annotation/Testable.class
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/function/
   229 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/function/Try$1.class
  5986 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/function/Try$Success.class
  5682 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/function/Try$Failure.class
  5599 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/function/Try.class
   506 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/function/Try$Transformer.class
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/support/
  6255 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/support/ReflectionSupport.class
  2263 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/support/ModifierSupport.class
  8717 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/support/AnnotationSupport.class
  1350 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/support/ClassSupport.class
  1435 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/support/HierarchyTraversalMode.class
     0 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/logging/
  4103 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/logging/LogRecordListener.class
  6452 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/logging/LoggerFactory$DelegatingLogger.class
   855 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/logging/Logger.class
  2080 Sun Apr 07 19:28:06 EDT 2019 org/junit/platform/commons/logging/LoggerFactory.class
 14235 Fri Nov 30 20:17:38 EST 2018 META-INF/LICENSE.md
   316 Fri Apr 13 20:35:52 EDT 2018 META-INF/LICENSE-notice.md
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/junit/
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/junit/platform/
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/junit/platform/commons/
     0 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/junit/platform/commons/util/
 10721 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/junit/platform/commons/util/ModuleUtils.class
  4859 Sun Apr 07 19:28:14 EDT 2019 META-INF/versions/9/org/junit/platform/commons/util/ModuleUtils$ModuleReferenceScanner.class

C:\Users\David Holberton\grad69groovycli>

git remote add origin git@github.com:ashburndev/grad69groovycli.git
git branch -M main
git push -u origin main
```

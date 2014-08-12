Weird uses constraint violation in JBoss AS 7.2
===============================================

See [this Stack Overflow question][so] for details.

Building
--------

Using [Gradle][gradle]:

    $ gradle zipJars

Output is placed in `build/libs` (individual jars) and `build/distributions` (a
zip file containing all the jars).

[gradle]: http://www.gradle.org
[so]: https://stackoverflow.com/questions/17317349/why-are-uses-constraints-violated-when-both-chains-end-in-the-same-bundle

test_dev
------------------------------------------------------------------------------------------------------
test_dev is my simple java app to perform back-end assessments,
examples :
* Dani's godaddy assessment exam 
==> according to me, the most appropriate data structure to use would be Map<String, HashSet<String>> if we don't consider sorting
==> then it might be TreeMap<String, TreeSet<String>> if we do consider sorting


---------------------------------------------

DEPENDENCIES
------------------------------------------------------------------------------------------------------
* The application runs with java 8 or higher,
* uses maven for dependency handling

------------------------------------------------------------------------------------------------------
PACKAGING
------------------------------------------------------------------------------------------------------
* first clone project from github
https://github.com/derrickrose/test_dev.git

* point path inside project directory, in my case as an example I am using ubuntu
'$ cd Documents/perso/projects/test_dev'

* be sure the path is pointing inside the application directory
in my case the welcome prompt shows frils@boss:~/Documents/perso/projects/test_dev$

* to build the project, enter the following command and note a BUILD SUCCESS
----
    mvn clean install
> !!! To skip the tests use parameter : -DskipTests

------------------------------------------------------------------------------------------------------
BEST PRACTICES
------------------------------------------------------------------------------------------------------
* Java best practices site : https://www.codejava.net/coding/10-java-core-best-practices-every-java-programmer-should-know

------------------------------------------------------------------------------------------------------
WHAT NEXT ? 
------------------------------------------------------------------------------------------------------
* other assessment exams
* example of perf check using mysql http://www.dbazine.com/oracle/or-articles/tropashko4/

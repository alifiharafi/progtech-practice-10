# progtech-practice-10
Practice #10 - Programming Technique for D4 POLBAN

Author **@alifiharafi**

In this exercise, we will learn about assert statement (Java assertions) using `DataRoles.java`.

## QUESTS
1. How to display custom message of assertion using command line? 
2. How to display custom message of assertion ONLY for class Research Roles using command line?
3. Is it possible to show all custom message of assertions? If it is possible how to do it?
   - OR - 
   Is it ONLY possible to show custom message of the assertion that was first discovered (assertion in the earlier line)? WHY?
4. Update Engineer Roles Class using EXCEPTION with "AssertionError"!
5. FIX the codes, make sure you don't have any error!
   Take a look to Engineer Tools Class. We want to remove selected elements of array list.
   If the assertion is ENABLED, removing elements of array list WORKS PERFECTLY. 
   BUT if the assertion is DISABLED, the elements of array list are NOT REMOVED. WHY?
6. At line 36, open the package comment. 
   Make a package according to the codes at the line. 
   Then execute this file using the java command accompanied by an "assertion parameter for the package".
Don't forget to provide a comprehensive explanation for each number!

## INITIAL OUTPUT
$ `java DataRoles`

They are a very specialized type of backend software engineer focusing on leveraging data. They operationlize and put predictive models into production, building pipelines, api and training models.

[Docker, Kubernetes, OpenShift, Tableau, MongoDB, ElasticSearch, Spark, TensorFlow, PyTorch]

## SAMPLE ASSERTION ERROR OUTPUT
`Exception in thread "main" java.lang.AssertionError: Data Ops is invalid research role`

`     at ResearcherRoles.displayRoleDesc(DataRoles.java:XX)`

`     at DataRoles.main(DataRoles.java:XX)`

## REFERENCES
- Main: https://www3.ntu.edu.sg/home/ehchua/programming/java/J5a_ExceptionAssert.html
- Description: https://medium.com/analytics-and-data/an-introduction-to-18-roles-in-the-data-ecosystem-d80d88fcbec7
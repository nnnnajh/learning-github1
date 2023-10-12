***Changes vs Snapshots***
**changes**
-----------------------------
ver1      ver2      ver3      ver4      ver5
File A ->  D1  ----------->   D2      
File B ------------------->   D1 ------> D2         
File C ->  D1  --->  D2     

**Snapshots**
-------------------------------
ver1     ver2      ver3      ver4      ver5                
  |        |        |          |        |             
File A    A1        A1         A2       A2            
  |        |        |          |        |            
File B     B        B          B1       B2
  |        |        |          |        |                 
File C     C1      C2          C2       C2               
-------------------------------------------------------
**\(1\) System level**: -system opion. Affects all uses and repositories on the system(administrative)     
**\(2\)Global\(User\)**: -global option. Affects all repositories of a current user   
**\(3\)Local level**: -local option. Specific to the current repository     
Each level overrides values in the previous level: system -> global -> local     

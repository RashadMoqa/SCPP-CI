These data and result files are used in: <br />
"Online and Offline Packing Cylinders in a Cylindrical Container"<br />
The objective is to maximize the volume utilization of the container.


***Offline 2D-CPP Problem***

**1- Equal circles**

*Data*: circle radius taken from Packomania website http://hydra.nat.uni-magdeburg.de/packing/cci/cci.html <br />
*Results*: folder "equal results" <br />
*Example*: file "cci10.txt" has center coordinates for n=10 equal circles: <br />
&nbsp;&nbsp;&nbsp;&nbsp; id xi yi <br />
&nbsp;&nbsp;&nbsp;&nbsp; .. .. ..

**2- Unequal circles**

*Data*: folder "beasley" taken from https://people.brunel.ac.uk/~mastjjb/jeb/orlib/circleinfo.html <br />
The format of these data files is: <br />
number of circles (n), 3 values for the container radius <br />
for circle i (i=1,2,...,n) in turn: <br />
&nbsp;&nbsp;&nbsp;&nbsp; circle radius <br />
*Results*: folder "beasley results" <br />
*Example*: file "c10_6.58.txt" for n=10, R=6.58 has coordinates: <br />
&nbsp;&nbsp;&nbsp;&nbsp; ri xi yi <br />
&nbsp;&nbsp;&nbsp;&nbsp; .. .. ..

***Online 2D-CPP Problem***

*Data*: folder "unequal shuffled" taken from http://hydra.nat.uni-magdeburg.de/packing/ccir/ccir.html <br />
The format of these data files is:<br />
&nbsp;&nbsp;&nbsp;&nbsp; n <br />
&nbsp;&nbsp;&nbsp;&nbsp; id ri <br />
&nbsp;&nbsp;&nbsp;&nbsp; .. .. <br />
*Results*: folder "unequal shuffled results" <br />
*Example*: file "ccir10.txt" for n=10, has coordinates: <br />
&nbsp;&nbsp;&nbsp;&nbsp; id ri xi yi <br />
&nbsp;&nbsp;&nbsp;&nbsp; .. .. .. ..

***Offline SCPP-CI Problem***

These problems are 3D Cylindrical packing adjusted from the 3D rectangular packing <br />
*Source*: folder "br" from https://people.brunel.ac.uk/~mastjjb/jeb/orlib/thpackinfo.html  <br />
*Data*: folder "cbr", the format of these data files is:     <br />
Number of test problems (100)     
For each problem p (p=1,...,100) the data has the format     
shown in the following example:

     Example:

     1              the problem number p
     110 587        container R, H
     10             number of cylindrical item types m
     1 15 108 20
     2 12 110 11    where there is one line for each cylinder type id
     3 ...................
     etc for m lines
     The line for each cylindrical item type contains 4 numbers:                         
     cylindrical type id, ri, hi, n cylinders of type id

*Results*: folder "cbr results" <br />
*Example*: file "cbr2_1.txt" for p=1 of class=2, has coordinates: <br />
&nbsp;&nbsp;&nbsp;&nbsp; id ri hi xi yi zi <br />
&nbsp;&nbsp;&nbsp;&nbsp; .. .. .. .. .. .. 

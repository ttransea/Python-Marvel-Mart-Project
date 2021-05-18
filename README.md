# Marvel-Mart-Project
Marvel Mart is the worldwide department store chain which has been providing both online and offline sales of a variety of  products for many years. The provide services to countries all over the world and have stores in many countries. Marvel Mart divides their order up by an alphabetical priority labeling system: 

    C: Critical (most essential to be delivered quickly and accurately) 

    H: High 

    M: Medium 

    L: Low 

There are several columns of data for sales: 

    Unit Price: money collected for sale of 1 unit 

    Unit Cost: money spent for purchase of 1 unit 

    Total Revenue: money collected for sale of the collection of units 

    Total Cost: money spent for purchase of the collection of units 

    Total Profit: Total Cost - Total Revenue (profit)      

The rest of the columns should be self-explanatory. <br />
<br /> MM_Sales.csv is the original data with these errors: incorrect data and missing data\
The errors are detected in those columns: <br />
  <br /> Country   (either missing OR will be a number as a string)\
   Item Type   (either missing OR won't be a valid Item Type from the other ones listed)\
  Order Priority   (either missing OR won't be a valid priority code of 'C', 'H', 'M', 'L', or 'NULL')\
  Order ID   (either missing OR won't be a number) <br />
  
  MM_Sales_cleaned.csv is the processed data after cleaning all the NULL and/or incorrect values.  <br />
   
Analyzed resulted are written to MM_Rankings.txt and MM_Calc.txt    <br />

Documentation.docx describes how the process is conducted.

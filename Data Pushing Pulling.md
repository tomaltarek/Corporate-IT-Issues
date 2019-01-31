# Data Pushing Pulling 

## Introduction 
Data pulling and pushing is a common scenario in corporate world. 

Data travels between heterogeneous systems. Suppose you need to feed some data from a legacy system to your corporate ERP system.

This data I am talking about is not finished data , it is kind of raw data  that you need to use for other purpose. 

Data push-pull also happens dealing with external customers. 


Usually data is written in a text file in comma delimited or other prefered format. Most of the cases, the text files are made out of a database, may be it is a query to a table on certain point of time. In the database a schedule job can be setup that runs the query on a certain time and produce a file with the data and dump the file on a folder. 

Data pushing pulling occurs between: 
- With Internal Customers 
- [With External Customers](#With-External-Customers)


## With Internal Customers: 
Once  database dumps a file on a folder, other scripts coudl be written to pick the file and push it to other location. At final point a schedule job is created on os level that runs the scripts on defined time. 
These schedules jobs should be setup on a server that runs 24 hours. Server could be database server, application server or any other kind of. 

When receiver receives the file, they usually use therir own script to cleanse the data, format them and finally fetch them to their system. 


With external customers: 
In case of external customers, prefered method is using ftp site.




Code block test :
```C
/*
@tomal tarek,arcola
This program can exit even if the end of the file is not reached


*/

#include<stdio.h>
#include<stdlib.h>

int main(void)
{
    int x;
    puts("give 1 to exit the program right now or give any integer to last until end of program");
    scanf("%d",&x);
    if (x==1)
    {
        puts("exiting without further doing sorry");
        exit(EXIT_SUCCESS);
    }

    else
        puts("has reached end of program");
}

```


## With External Customers: 
In case of external customers, prefered method is using ftp site. 

<pre><code>
test code 
test code 
</code></pre>


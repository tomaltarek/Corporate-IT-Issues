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




Some basic Git commands are:
```
import java.util.LinkedList;
import java.util.Queue;

public class queueExample {
	
	public static void main(String []args) {
		
		Queue<Integer> abc=new LinkedList<>(); 
		
		abc.add(2); 
		abc.add(45); 
		abc.add(30);
		abc.add(10); 
		abc.add(50); 
		System.out.println("-------this program demonstrate queue------");
		System.out.println("Original queue is: "+abc);
		//abc.peek(); 
		System.out.println("Size of the queue is : "+abc.size());
		System.out.println("The first value of queue is :"+abc.peek());
		//abc.clear(); // to remove all elements 
		abc.remove(); // removing a 
		System.out.println("After removing one element :"+abc);
		System.out.println("is the queue empty: "+abc.isEmpty());
		
	}

}
```


## With External Customers: 
In case of external customers, prefered method is using ftp site. 

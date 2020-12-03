# FPRT2

1) What do the following commands do and how would you use them?
All the below commands are having some options can be specified after the command like -v verbose,  -a all etc.,
1.	Awk
2.	Curl – Curl used to transfer the data from or the server with out any user interaction
3.	Wget – wget is a command line tool used to download data from the internet. Using this we can download multiple files at a time / a single file
4.	Head – head prints first 10 number of lines of the specified file.by default it prints 10 lines we can increase the by specifying the number of lines -n 12
5.	Tail – Tail is inverse of the head it prints last line of the file. Ex: while we are checking Heroku logs we will use tail -f for checking the updated lines
6.	Less – Less is used to show one page at a time of the whole file
7.	Cat – cat command can used for reading/view/concatenate multiple files
8.	Touch – Touch is used to create a file without any content in it. 
9.	Netstat – it is command mostly used to check connectivity like network connection like udp tcp listing ports on pc/network
10.	Tcpdump – it is also related to networking by using this command we check what traffic is going or coming to pc(technical term packet sniffing it is also used in hacking to check what traffic is going through the network by hacker/ network admins) we can save the data or we can see them on terminal its self

2) What is an Index? Explain different indexing in mongodb and postgresql?
	Index in data base means the indicator by which we can retrieve the data from the database
Ex: we can use books example where index page referes to the what data present in the book.
Indexing in mongo db indexing can be done on collection level or on filed level. While we are executing the query if no index is passed then mongodb must go through every document of the given collection. In mongo db it only automatically assigns a primary key/id  to each and every document we have inserted into it.
There are different types of indexing single field, compound,multikey etc., 

Indexing in postgresql:
	In sql the user can specify the key or primary key for the particular value with combination of auto increment and unique. Through which user can index the required data for them. Types are single-column, multi-column and unique indexing etc.,
	

3) How to know which process listens on a specific port?
We can use the above command like netstat with option -a to view all connections or we can check the taskmanager(just pid) / in resource monitor under network tab.

4) What is the difference between normalization and denormalization and what are the advantages and disadvantages of them?



5)  Difference between inner and outer join?
	It is a type of join operation used in sql. Inner join returns only the rows that both tables have in common are returned. Outer join returns all the rows if there is no common also.

6) What is Cache?
	Cache is a type of memory storage which is used to store high frequently used data temporarily from the main memory to process because of its high-speed data access. the process of accessing data and storing data from the cache memory is known as caching. 
7) What is virtual memory? 
Virtual memory is a memory management technique where secondary memory can be used as if it were a part of the main memory. It used used mainly to compensate the shortages of the physical memory.

9) What is paging and why do we need it?
	In web development: Paging means dividing long pages into small pages to simplify viewing of website.
Pagination is very important in websites which are having more content the viewer/user can view them in small pages which are automatically sorted in the updated time/ the sorting order they wish.it reduces the scrolling behaviour of the user and the user can easily can browse the specific page he/she likes. We can do this by providing page numbers for the specific pages or by using scroll bottom to load more method or by using load more option to the user.

In os :
	Paging is a type of memory management similar to in web development we use the paging to retrieve the secondary storage into the main memory in the form of pages and process in the pages(chunks).

10) What is load balancer and what are its advantages?
	Load balancer is used to divided the incoming requests(or serving  the request to the servers) or load across multiple servers with high availability and reliability by sending the incoming requests to servers which are available. It also provides to add new servers or remove failure servers while answering to other incoming requests. It is placed before the server and router. The advantages of using the load balancer are reduced downtime, scalable, less redundancy and effiency. 

11) What is CDN and what are its advantages?
	CDN – content delivery network 
	It is used to deliver the content to user from the nearest geolocation to the user because the CDN providers setups a network of servers in different geo locations and provides the content to user from the nearer to users geo location. By using this type of network  we increase our website speed and performance and with high quality. 
Advantages of using the cdns are fast, more concurrent users, availability of content. 

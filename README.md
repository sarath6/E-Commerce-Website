# E-Commerce-Website
The application aims at providing an e-commerce website that sell products online and study the behavior of their online customers.
The piece of software to which the present document refers, is an e-commerce website that sell products online and study the behavior of their online customers. The site will allow the administrator to maintain products and categorize them. A search facility is provided for the customer to zero in on specific products. The site requires the customer to register before using the services. The customer will also be provided with facility to see the previous purchases and recent interests.
As the customer parses through the WebPages the application tracks his interests and logs them. It identifies the search criteria used and whether the search yielded him a result. The details are logged for updating the contents or products unavailable presently and have a demand. The administrator studies the log file to provide additional support. The next time the customer visits the website he is intimated of the recently added products and those items that failed to return a result in the previous search. A facility to compare few products is also available to the customer in-order to identify a product. 

#	Product Functions
The functions provided by the application are

	Customer Registration
	Product Maintenance
	Shop Product
	Search Product
	Log Analyzer
	Feedback Monitor
#Modules
Customer Registration
Allows the customer to provide his personal details with photo for registration. The details are updated to the customer table. Each customer is provided with unique id and password. The registered customers can be viewed by the administrator.
Product Maintenance
The admin identifies the product and creates the catalog. The details of the product, its images, specification, price and rating (based on feedback) are displayed. The admin can update the details or remove the product from the catalog.
Shop Product
The registered customers are allowed to identify and purchase products. The module tracks the behavior of parsing the products and identifies the customer interest. The details of his interests are shown to him the next time he visits.

#System Requirement

Software requirement
Operating System	: Windows 2000 or Higher	
Platform	: .Net (C#)
Backend	: Ms-SQLServer

Hardware Requirement (Minimum)
Processor			: PIV
Ram				: 512 Mb
Hard Disk			: 10 GB space

#Test Cases

6.6.1 Test Case 1
Module : Login
Filename : login.jsp

Test	Input	Recvd Output	Act Output	Desc

Valid Login	
User Id, Password	
Login Success	
Login Success	
Test Passed!
Control Transferred to Menu


Invalid Login	
User Id, Password	
Login Failed	
Login Failed	
Test Passed!
Try Again


Invalid Login	
Null,Null	
Login Failed	
Login Failed	
Test Passed!
Try Again









6.6.2 Test Case 2
Module : Change Password
Filename : cpwd.jsp

Test	Input	Recvd Output	Act Output	Desc

Valid Password, Password updation	
Old Pwd, New Pwd & Conf Pwd	
Success	
Success	
Test Passed!
Password Changed


Invalid Password, Password updation Failed	
Old Pwd, New Pwd & Conf Pwd	
Failed	
Failed	
Test Passed!
Old pwd incorrect or new pwd & conf pwd mismatch








6.6.3 Test Case 3
Module : Registration
Filename : reg.jsp

Test	Input	Recvd Output	Act Output	Desc

Registration	
User Details	
Success	
Success	
Test Passed!
User created with id and password


Registration	
User Details	
Failed	
Failed	
Test Passed! Incomplete or invalid data.








6.6.4 Test Case 4
Module : Product Maintenance
Filename : addproduct.jsp

Test	Input	Recvd Output	Act Output	Desc

Create Product 	
Product Info	
Success	
Success	
Test Passed!
Product created, image uploaded


Create Product 	
Product Info	
Failed	
Failed	
Test Passed! Invalid data or picture file not found











6.6.5 Test case 5
Module : Search Products
Filename : search.jsp

Test	Input	Recvd Output	Act Output	Desc

Display Products	
Product ID	
Success	
Success	
Test Passed!
Data displayed


Display Products	
Product ID	
Failed	
Failed	
Test Passed! Product not found.








6.6.6 Test Case 6
Module : Shop Products
Filename : shopprod.jsp

Test	Input	Recvd Output	Act Output	Desc

Purchase Products	
Product ID, category, qty	
Success	
Success	
Test Passed!
Order placed


Purchase Products	
Product ID, category, qty	
Failed	
Failed	
Test Passed! Product not found.














6.6.7 Test Case 7
Module : Set Feedback
Filename : setfeed.jsp

Test	Input	Recvd Output	Act Output	Desc

Feedback	
Order id, comments	
Success	
Success	
Test Passed!
Feedback saved


Feedback	
Order id, comments	
Failed	
Failed	
Test Passed! Invalid Order.








6.6.8 Test Case 8
Module : Horizontal aggregation
Filename : pivot.jsp

Test	Input	Recvd Output	Act Output	Desc

Crosstab 	
Src, dest table, comm. Column, row param, col params	
Success	
Success	
Test Passed!
Pivot generated and cross tab displayed


Crosstab 	
Src, dest table, comm. Column, row param, col params	
Failed	
Failed	
Test Passed! Check pivot inputs










First launch 2 or 3 instances that need to be added to target groups.

Create the target groups
	1) Provide the target type to instances and provide the name
	<img width="1917" height="766" alt="image" src="https://github.com/user-attachments/assets/b46eff14-b9a2-4ffe-88b6-2742defacc73" />

	2) Provide protocol as HTTP and VPC details (VPC should be same where your instances are hosted)
	<img width="1918" height="818" alt="image" src="https://github.com/user-attachments/assets/9a10a8f8-8856-4138-8420-58924de8d5ed" />

	
	3) Add the created instances to target groups 
	Select the instance -- include as pending below
	<img width="1918" height="852" alt="image" src="https://github.com/user-attachments/assets/8ad27f6b-174d-4bff-8110-ae698350be5d" />

	
	Create the load balancer
	Choose the load balancer as application load balancer
	
	Provide the name and select options
	<img width="1822" height="652" alt="image" src="https://github.com/user-attachments/assets/edbb1978-a6b1-43fd-9ac8-680b3bb44000" />

	
	
	Then choose the vpc target group and create new security group and configure as below
	<img width="1783" height="670" alt="image" src="https://github.com/user-attachments/assets/a995e16a-4686-413a-bf1b-f8d7f03c9f2a" />

	<img width="1803" height="812" alt="image" src="https://github.com/user-attachments/assets/428a9e5f-8d53-4c65-8157-5ea6d96cffa0" />

	
	Now select the target groups in listener 
	
<img width="1662" height="517" alt="image" src="https://github.com/user-attachments/assets/3e2f326f-3bf1-476d-bcce-d9e891674eb7" />

	
	Create load balancer.
	
	Try access using the load balancer Dns name
	
	<img width="1795" height="480" alt="image" src="https://github.com/user-attachments/assets/13ed3c1c-1f89-4763-87d6-a51128d5be35" />

	
	<img width="1918" height="537" alt="image" src="https://github.com/user-attachments/assets/43a506d4-c965-4d37-9aee-a3d3157a4acb" />

	
	In the ec2 machine install any web server and provide these content in the html file.
<img width="1978" height="6522" alt="image" src="https://github.com/user-attachments/assets/fb431627-46ba-41c3-860d-f533528eacc0" />

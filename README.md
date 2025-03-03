# AWS-Project-1
# For detailed step by step guide blog of the project: Read out Here ->  
https://medium.com/@killerjohnson513/deploying-and-hosting-a-web-application-on-aws-ec2-with-apache2-84b8fe5a850e  
Deployed App using Apache2 to AWS
# Prerequisites
1.An AWS account.  
2.knowledge of Linux commands and Git.  
3.An SSH client(Terminal for macOS/Linux).  
4.A GitHub account. 

# Step 1: Uploading your Web Application to GitHub  
1. Initialize Git in your Project Directory.  
2. Add Files to the repository.  
3. Create a New GitHub Repository.   
Go to GitHub and create a new repository.   
Copy the repository URL  
4. Push your files to GitHub.

# Step 2: Launching an EC2 Instance  
1. login to AWS console.  
2. Go to EC2 Dashboard -> click on EC2 under the service menu.  
3. Launch an Instance:  
Click on Launch Instance.  
Choose an Amazon Machine Image(AMI).  
Select Instance type.  
Set up the key pair(Login), download the .pem key file and save it securely.  
Review and launch the instance.

# Step 3: Connecting to your EC2 Instance  
Once instance is running:  
1. Open your terminal and SSH client.  
2. Navigate to the directory where your .pem key is stored.  
3. Run the following commands to connect:  
   chmod 400 your-key.pem  
   ssh -i your-key.pem your-AMI@your-ec2-public-ip
   
# Step 4: Installing Apache2 Web Server
After connecting to your instance:  
1. Update package lists.    
2. Install Apache2.  
3. Enable and start the apache service.
4. verify Apache installation by visiting http://your-ec2-PublicIP in your browser. You should see the Apache default page.

# Step 5: Cloning Your Web Application on EC2  
# Step 6: Access your application  



 

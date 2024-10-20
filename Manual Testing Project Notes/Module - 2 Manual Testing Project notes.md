## Manual Testing Project

Project introduction
--
- Understanding & Explore the Functionality (FRS)
- Estimation - efforts
- Test Plan
- Writing Test Scenarios
- Writing Test Cases & Reviews
- Environment Setup & Build deployment
- Test Execution
-  Bug Reporting & Tracking
- Sanity Testing, Re-Testing & Regression Testing
- Test Sign off

### Project Vs Product

Project introduction
--
Product
-- 
-eCommerce product/Application

eCommerce
--
-   Login
-   Search for products/items
-   Add then to cart
-   Do payment
-   Product will be delivered.
-   Returns the product
        etc....
       

- Frontend -- public
- Backend - - Admins

- URL : https://demo.opencart.com/Customer:opencart

- Design: Mockup screens
- Requirement - we have highlighted in FRS



1) MySQL Database
 2) Apache server

 - Frontend(browser) -> web app(server -apache) - DB(backend data)

- XAMMP apps use to get MySQL DB and Apache server
- release note : how to deploy , find bug, new features, installation tools, step by step method along with build from developer.

 Opencart Build Deployment/Installation
--
1) Opencart download location:
https://www.opencart.com/index.php?route-cms/download


2) XAMPP for apache, mysgi. and php installation.
(Recommended versions: 7.3.25 / PHP 7.3.25)
Download Link: https://www.apachefriends.org/download.html



Step by step XAMPP Installation:

- Setup XAMPP

![Screenshot 2024-10-16 180938](https://github.com/user-attachments/assets/d7793dc1-39f6-40f9-9478-2cf3160ce5b4)


![Screenshot 2024-10-16 180927](https://github.com/user-attachments/assets/1c71b569-4dce-4006-8499-04d99b0e59ea)


- Finish setup

![Screenshot 2024-10-16 180913](https://github.com/user-attachments/assets/8109eb48-1802-4fd6-bdd8-b54f1e79cdd3)

- start XAMPP

![Screenshot 2024-10-16 180856](https://github.com/user-attachments/assets/91056905-f7fe-470e-8191-d927a1c111f9)

- Run XAMPP

![Screenshot 2024-10-16 180838](https://github.com/user-attachments/assets/11f5471b-8dd8-4a06-9236-41676d727bc3)



```
 If there is any issue to start Apache then execute below command In CMD
   
     Kill process using below command
          taskkill /F /PID 7028
```

 3) Copy opencart folder(Step1) in to below location.

     `C:\xampp\htdocs`


4) After copying rename the folder ex: opencart

5) Rename files
``` 
Go to C:\xampp\htdocs\opencart\upload
Rename file 'config-dist.php" to 'config.php'

Go to C:\xampp\htdocs\opencart\upload\admin
Rename file 'config-dist.php' to 'config.php'
```

6) Connect to the database and create DB.
 - DB Access URL: http://localhost/phpmyadmin/
 - Create new database 'openshop' (Refer the screenshots below to create new Database in MySQL)

7) Open the site
   `http://localhost/opencart/`
 - Click on upload

![Screenshot 2024-10-16 182500](https://github.com/user-attachments/assets/71201d88-8389-440b-9253-13dc1a60abf6)

![Screenshot 2024-10-16 182245](https://github.com/user-attachments/assets/a94a4273-6e6b-4a9a-9910-cdcf224eaf9a)

![Screenshot 2024-10-16 182256](https://github.com/user-attachments/assets/36e0fc2f-f8ff-473c-9fdb-3d136f7f81fe)

8) configuration & provide Database connection details

![Screenshot 2024-10-16 182416](https://github.com/user-attachments/assets/85aa1651-f33c-41c8-8cfe-2c0e478818fb)

9) Installation complete & Go to location

   `C:\xampp\htdocs\opencart\upload`
- Delete install folder.

![Screenshot 2024-10-16 182439](https://github.com/user-attachments/assets/a32598b8-6f32-4b0d-9482-c1f37ba654ea)

10) Go to Application URL

- Front End Store URL: http://localhest/opencart/upload/
- Backend Admin URL; http://localhost/opencart/upload/adimin/

- if everything done we can stop MYSQL DATABASE and Apache server

![Screenshot 2024-10-16 183833](https://github.com/user-attachments/assets/1bd09880-d81c-4100-bf25-a79e6583cbaf)


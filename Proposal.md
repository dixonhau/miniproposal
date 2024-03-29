<!DOCTYPE html>
<html>

<h1>Title</h1>
<body>Face Recognition Attendance System</body>
<p>https://github.com/YuHengKit/FaceRecognitionSystem</p>

<h1>Team HKL</h1>
<p>Members : </p>
<p>1. HAU ZHE XUAN</p>
<p>2. KIT YU HENG</p>
<p>3. LIM JUN SHIUN</p>

<h1>Overview</h1>

<p>When the system is activated, camera will keep operate for a period to detect the face and capture it as image. Then, the data of image taken will send to Raspberry Pi to process it to data that need to be send to Cloud Database.</p>
<p>The data of image will saved in Cloud Database that use for data storing. After that, the data stored will send to another Database to go through face recognition process. Data of image will be recognized and classify according to data saved in database. Classified face data will be send to Attendance System Management to data record purpose.</p> 
<p>The data of user such as ID, Name, Check In and Check Out Time will be recorded. If there is a feedback, it will be send to management based on the requirements.</p>

<h1>System Architecture</h1>
<img src="https://user-images.githubusercontent.com/11400016/67187028-ea143d00-f41b-11e9-87c2-511f3ec8c1cf.png" />

<h1>Domain Model</h1>
<img src="https://user-images.githubusercontent.com/11400016/67187139-2778ca80-f41c-11e9-9e0d-8ac02b5dc316.png" />

<h1>Entity-Relationship Diagram</h1>
<img src="https://user-images.githubusercontent.com/11400016/67187172-3b243100-f41c-11e9-8e39-abd7306cb451.png" />

<h1>Database Tables</h1>
<img src="https://user-images.githubusercontent.com/55488934/67191918-20a28580-f425-11e9-8311-b764b9709a29.jpg" />
<img src="https://user-images.githubusercontent.com/55488934/67191919-20a28580-f425-11e9-9e5a-5b3f7a45aad8.jpg" />
<p>Database table will store the information of employees such as ID, name, age, job title and mobile phone. It also used to store the link which directed to the employees' photo file for face recognition. Another database was created to store the username and password for authorized users to access the attendance system for record checking.

<h1>User Interface</h1>
<img src="https://user-images.githubusercontent.com/55488934/69539897-63292600-0fc0-11ea-9f1b-553cb64dcd4d.jpg" />
<img src="https://user-images.githubusercontent.com/55488934/69539903-66bcad00-0fc0-11ea-8783-d9326c51b03e.jpg" />
<p>A login page is used to ensure only the one who has the authority can access the data. After the correct username and password is entered, the second page will be shown with the attendance details of employees. Drop down menu for years and months, as well as search widget was added to provide convenient for users.</p>

<h1>Django server based Website</h1>
<p>Python Django </p>

<h1>Class Diagram</h1>
<img src="https://user-images.githubusercontent.com/11400016/69170362-eec03400-0b34-11ea-9c4d-0a9aa00d3b3b.png" />

<h1>Database Table</h1>
<img src="https://user-images.githubusercontent.com/11400016/70039481-04cdfa00-15f5-11ea-9fbb-ff192d5572bd.png" />

<h1>Normalized Table</h1>
<img src="https://user-images.githubusercontent.com/11400016/70039442-ecf67600-15f4-11ea-8384-3534617b4e74.PNG" />

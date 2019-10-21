<!DOCTYPE html>
<html>

<h1>Title</h1>
<body>Face Recognition Attendance System</body>

<h1>Team HKL</h1>
<p>Members : </p>
<p>1. HAU ZHE XUAN</p>
<p>2. KIT YU HENG</p>
<p>3. LIM JUN SHIUN</p>

<h1>Overview</h1>

<p>When the system is activated, camera will keep operate for a period to detect the face and capture it as image. Then, the data of image taken will send to Raspberry Pi to process it to data that need to be send to Cloud Database.</p>
<p>The data of image will saved in Cloud Database that use for data storing. After that, the data stored will send to another Database to go through face rocognition process. Data of image will be recognized and classify according to data saved in database. Classified face data will be send to Attendance System Management to data record purpose.</p> 
<p>The data of user such as ID, Name, Check In and Check Out Time will be recorded. If there is a feedback, it will be send to management based on the requirements.</p>

<h1>System Architecture</h1>
<img src="https://user-images.githubusercontent.com/11400016/67187028-ea143d00-f41b-11e9-87c2-511f3ec8c1cf.png" />

<h1>Domain Model</h1>
<img src="https://user-images.githubusercontent.com/11400016/67187139-2778ca80-f41c-11e9-9e0d-8ac02b5dc316.png" />

<h1>Entity-Relationship Diagram</h1>
<img src="https://user-images.githubusercontent.com/11400016/67187172-3b243100-f41c-11e9-8e39-abd7306cb451.png" />

<h1>Database Tables</h1>
<img src="https://user-images.githubusercontent.com/11400016/67181897-76206780-f410-11e9-87a8-4c0f67f64bbf.jpg" />

<h1>User Interface</h1>
<img src="https://user-images.githubusercontent.com/11400016/67182458-d82d9c80-f411-11e9-9499-4dcc380e1d7e.jpg" />

<h1>Django server based Website</h1>

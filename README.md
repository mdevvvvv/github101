Github 101

<h1>Git คืออะไร</h1>
คือ Version Control เป็นระบบจัดเก็บและควบคุมการเปลี่ยนแปลงที่เกิดขึ้นกับไฟล์ชนิดใดชนิดหนึ่ง ไม่ว่าจะเป็น Text หรือ Binary 

<h1>Git Workflow</h1>
Create->Init->Add-Push->Pull->Push

<h1>Git Status</h1>
Untracked ไฟล์ใหม่ ยังไม่ได้เอาเข้าระบบ
Working Directoty กำลังทำงาน มีการแก้ไข
Staged พร้อมรอ ตรวจสอบ (commit)
Local Repository เก็บสถานะที่มีการบันทึกข้อมูลการเปลี่ยนแปลง ไว้ที่ Local
Remote Repository เก็บสถานะที่มีการบันทึกข้อมูลการเปลี่ยนแปลง ไว้ที่ Server

<h1>Install</h1>

<h1>check version</h1>
git --version

<h1>config git</h1>
git config --list
git config --global user.email "ritnam.thanakrit@gmail.com"<br/>
git config --global user.name "mdevvvvv"

<h1>Create & Init</h1>
git init
git remote add origin https://github.com/mdevvvvv/github101.git
git status

<h1>Clone</h1>
git clone <url>

<h1>Add</h1>
git add <file>
git add <directory>
git add .

<h1>Commit</h1>
git commit -m "message"

<h1>Push</h1>
git push -u origin master

<h1>Pull</h1>
git pull --all
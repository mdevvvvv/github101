<h1>Github 101</h1>

<h1>Git คืออะไร</h1>
คือ Version Control <br/>เป็นระบบจัดเก็บและควบคุมการเปลี่ยนแปลงที่เกิดขึ้นกับไฟล์ชนิดใดชนิดหนึ่ง ไม่ว่าจะเป็น Text หรือ Binary <br/>

<h1>Git Workflow</h1>
Create->Init->Add-Push->Pull->Push<br/>

<h1>Git Status</h1>
Untracked ไฟล์ใหม่ ยังไม่ได้เอาเข้าระบบ<br/>
Working Directoty กำลังทำงาน มีการแก้ไข<br/>
Staged พร้อมรอ ตรวจสอบ (commit)<br/>
Local Repository เก็บสถานะที่มีการบันทึกข้อมูลการเปลี่ยนแปลง ไว้ที่ Local<br/>
Remote Repository เก็บสถานะที่มีการบันทึกข้อมูลการเปลี่ยนแปลง ไว้ที่ Server<br/>

<h1>Install</h1>

<h1>check version</h1>
git --version

<h1>config git</h1>
git config --list<br/>
git config --global user.email "ritnam.thanakrit@gmail.com"<br/>
git config --global user.name "mdevvvvv"<br/>

<h1>Create & Init</h1>
git init<br/>
git remote add origin https://github.com/mdevvvvv/github101.git<br/>
git status<br/>

<h1>Clone</h1>
git clone [url]

<h1>Add</h1>
git add [file]<br/>
git add [directory]<br/>
git add .<br/>

<h1>Diff</h1>
git diff

<h1>Commit</h1>
git commit -m "message"

<h1>Push</h1>
git push -u origin master

<h1>Pull</h1>
git push<br/>
git pull --all
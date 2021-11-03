Github 101

Git คืออะไร
คือ Version Control เป็นระบบจัดเก็บและควบคุมการเปลี่ยนแปลงที่เกิดขึ้นกับไฟล์ชนิดใดชนิดหนึ่ง ไม่ว่าจะเป็น Text หรือ Binary 

Git Workflow
Create->Init->Add-Push->Pull->Push

Git Status
Untracked ไฟล์ใหม่ ยังไม่ได้เอาเข้าระบบ
Working Directoty กำลังทำงาน มีการแก้ไข
Staged พร้อมรอ ตรวจสอบ (commit)
Local Repository เก็บสถานะที่มีการบันทึกข้อมูลการเปลี่ยนแปลง ไว้ที่ Local
Remote Repository เก็บสถานะที่มีการบันทึกข้อมูลการเปลี่ยนแปลง ไว้ที่ Server

Install

check version

<h1>config git</h1>
git config --global user.email "ritnam.thanakrit@gmail.com"<br/>
git config --global user.name "mdevvvvv"

Create & Init
git init

Clone

Add
git remote add origin https://github.com/mdevvvvv/github101.git

Push
git push -u origin master

Pull

Commit


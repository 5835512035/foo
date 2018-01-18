# foo project

## My foo
* item1
* item2

## วิธีการทำเริ่มต้นออกแบบเว็บ
* ลิงค์ในการทดสอบ[LINK MD] (https://github.com/5835512035/foo/edit/master/README.md)

* mkdir foo สร้างโฟลเดอร์ใหม่ขึ้นมา
* cd foo ทำการเข้าถึงในไฟล์
* echo "# foo" >>README.md เป็นการเขียนข้อความลงไปในไฟล์
* git init  คำสั่งนี้จะสร้างแฟ้มข้อมูลย่อยชื่อ .git ซึ่งเก็บแฟ้มโครงสร้างของ Git repository เปล่า ๆ ที่ยังไม่มีเนื้อหาใด
* git add README.md  ใช้ stage เพื่อติดตามตามความเปลี่ยนแปลงของไฟล์

* git config --global user.email "5835512035@psu.ac.th"
* git config --global user.name "5835512035"คือการระบุตัวตนโดยเราจะต้องใส่ชื่อกับอีเมล์ของเราให้ git จำไว้ เพื่อเวลาที่มีการแก้ไขจะได้รู้ว่าใครเป็นคนแก้ไข โดยอีเมล์แนะนำให้ใช้อันเดียวกับที่สมัคร GitHub ส่วนชื่อก็อะไรก็ได้ เหมือน username บน GitHub ก็ดี

* git commit -m "first commit" ใช้เพื่อบันทึกความเปลี่ยนแปลงที่เกิดขึ้นสู่ local repo
* git remote add origin https://github.com/5835512035/foo.git
* git remote -v 
* git push -u origin master
* Username for 'https://github.com': 5835512035 ใส่ชื่อ
* Password for 'https://5835512035@github.com': ใส่password

### ผลลัพธ์
* Counting objects: 3, done.
Writing objects: 100% (3/3), 212 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/5835512035/foo.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
* https://tupleblog.github.io/use-git-part1/ เว็บสอนทำ

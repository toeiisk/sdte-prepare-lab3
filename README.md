# SDTE 2020 Lab 3

## สิ่งที่ต้องทำ
1. Fork repo นี้
2. Clone repo ที่ fork ไปลงบนเครื่อง
3. สร้าง Folder ให้มีชื่อเป็นรหัสนักศึกษาตนเอง ใน folder lab
4. สร้างไฟล์​ index.html ใส่ Content อย่างใดก็ได้ แต่ให้มี Content เมื่อเปิดไฟล์มาให้มีข้อมูลแสดงให้เห็นอย่างน้อยดังนี้
- [ ] รหัสนักศึกษา
- [ ] ชื่อ สกุล
5. เพิ่ม link เพื่อเข้าถึงหน้า index.html ของรหัสนักศึกษาตัวเอง ใน files students.html ใน tag `<ul>...</ul>` ดังตัวอย่าง (ถ้ามีของคนอื่นใส่อยู่ก่อนแล้ว ให้แค่เพิ่ม, ถ้ามีการลบของคนอื่นจะไม่อนุญาตให้ผ่าน PR)

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Lab3</title>
  </head>
  <body>
    <h1>Welcome to LAB 3</h1>

    <ul>
      <li><a href="./lab/53070077/index.html">53070077</a></li>
    </ul>
  </body>
</html>
```
6. Commit & Push
7. สร้าง Pull Request เข้ามาที่ Repo หลัก โดยตั้งหัวข้อ PR ดังนี้ `รหัสนักศึกษา - Add profile` เช่น `53070077 - Add profile`
8. หากมี Conflict ในขั้นตอนการ Merge เกิดขึ้นให้แก้ไขให้เรียบร้อย
9. Lab จะเสร็จสิ้นเมื่อ PR ผ่าน และได้ Merge เข้า Branch main แล้ว สามารถดูผลลัพธ์การ Merge ได้ผ่าน Github pages https://saranonuan.github.io/sdte-lab3/

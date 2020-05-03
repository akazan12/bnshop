1. ทำการลง nodejs จากเว็บ nodejs.org สามารถดูวิธีการติดตั้งได้จาก https://playground.cmmakerclub.com/2016/07/javascript/%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%95%E0%B8%B4%E0%B8%94%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87-node-js-%E0%B9%81%E0%B8%A5%E0%B8%B0-npm-%E0%B8%9A%E0%B8%99-windows/

2. เมื่อทำการติดตั้งเสร็จให้โหลดไฟล์จาก github มาลงแล้วทำการ cd (โฟลเดอร์ที่โปรแกรมอยู่) 

3. แล้วทำการพิมพ์คำสั่ง npm install เมื่อทำการติดตั้งเสร็จแล้วให้ cd client แล้วทำการ npm install อีกหนึ่งครั้งเป็นอันเสร็จสิ้นการติดตั้งแล้ว

4. ทำการสร้างไฟล์ dev.js ขึ้นมา โดยเข้าไปที่ server แล้ว config แล้วทำการเพิ่มไฟล์ dev.js โดยใช้ code นี้

module.exports = {
    mongoURI:"mongodb+srv://benny:2004032339@cluster0-iscut.mongodb.net/test?retryWrites=true&w=majority"
}

5. ใช้คำสั่ง npm run dev ในการ run โปรแกรมขึ้นมา เมื่อกดแล้ว web browser จะเด้งขึ้นมาทันทีพร้อมกับเปิด localhost ให้เรียบร้อย แล้ว

— — ร้านค้าออนไลน์ด้วย MERN stack — —

จัดทำโดย

นายเบนนี่ บริทรีโอ 1600900920

เสนอ

อาจารย์ทศพล บ้านคลองสี่

วิชาการเขียนโปรแกรมเชิงวัตถุ

สาขาวิชาวิศวกรรมคอมพิวเตอร์

คณะวิศวกรรมศาสตร์

มหาวิทยาลัยกรุงเทพ

ภาคเรียนที่ 2 ปีการศึกษา 2562

— — — — — — — — — — — — — — — — — — — — — — — — — —

— — Clothing Shop with MERN stack — —

SUBMITTED BY

BENNY BITRIOL 1600900920

PRESENT

TODSAPON BANKLONGSI

OBJECT ORIENTED PROGRAMMING

DEPARTMENT OF COMPUTER ENGINEERING

SCHOOL OF ENGINEERING

BANGKOK UNIVERSITY

SEMESTER 2 YEAR 2019
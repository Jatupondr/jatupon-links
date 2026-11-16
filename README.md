# JATUPON · Atelier

เปิด `index.html` ในเบราว์เซอร์ได้ทันที ไฟล์นี้มี HTML, CSS, JavaScript, ไอคอน และฟอนต์ในตัว

## แก้ลิงก์และรูปโปรไฟล์

1. เปิด `index.html` ในโปรแกรมแก้ข้อความ แล้วค้นหา `const SITE` ที่ต้น `<script>`
2. แก้ `url` ใน `groups` → `links` หรือใน `socials` ใช้ URL เต็ม เช่น `https://...` หรือลิงก์อีเมลแบบ `mailto:...` ตั้งเป็น `''` หากยังไม่มีปลายทาง รายการจะขึ้นแบบกดไม่ได้
3. เพิ่ม ลบ หรือย้ายรายการในกลุ่มหรือย้ายข้ามกลุ่มได้ เลขหน้าลิงก์จะเรียงต่อกันอัตโนมัติ ตั้ง `featured: true` ให้รายการที่ต้องการใช้กรอบทอง และแก้คำโปรยใน `bio`
4. เว้น `profileImage: ''` เพื่อใช้ monogram J หรือใส่ URL รูป HTTPS หากใช้ไฟล์รูปใน repo ให้ใส่ชื่อไฟล์ เช่น `./profile.jpg` แล้วอัปโหลดรูปไว้ข้าง `index.html`

ปลายทางที่ตั้งไว้แล้วมี DRFX OpenChat, Billdee, LINE สั่งอาหารทะเล `@777dnvvc`, แชทกลุ่มอาหารทะเลบน Facebook และ LINE บอทเทรด `@drfx` ส่วน About Me, ข้อมูลบริษัท, หน้าดาวน์โหลด Billdee PostHub, ติดต่อร่วมงาน และ TikTok ยังรอ URL จริง

## Deploy บน GitHub Pages

1. สร้าง repository แล้วอัปโหลด `index.html` และ `README.md` ไว้ที่ root ของ branch `main` รวมรูปด้วยถ้าตั้ง `profileImage` เป็นไฟล์ใน repo
2. ไปที่ **Settings → Pages** เลือก **Deploy from a branch** แล้วเลือก **main** และ **/(root)** จากนั้นกด **Save**
3. เมื่อ GitHub Pages แสดง URL ให้เปิดหน้าเว็บผ่าน URL นั้น หากต้องการกำหนดภาพแชร์ ให้เพิ่ม `<meta property="og:url" content="…">` และ `<meta property="og:image" content="…">` ใน `<head>` โดยใช้ URL HTTPS ของหน้าและภาพที่เข้าถึงได้สาธารณะ

[คู่มือตั้งค่า GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

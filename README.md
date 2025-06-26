# 🌱 SPDP: Senior Project Digital Platform
### ระบบจัดการโครงงานนักศึกษาระดับปริญญาตรี

![Uploading Screenshot 2568-06-26 at 17.16.46.png…]()

## 📋 ภาพรวมโครงการ

โครงงานนักศึกษาในระดับปริญญาตรีเป็นโอกาสสำคัญที่ให้นักศึกษาได้นำความรู้ที่ศึกษามาประยุกต์ใช้ในการแก้ปัญหาจริง พร้อมทั้งฝึกทักษะการวางแผนงาน การพัฒนาโปรแกรม และการทำงานเป็นทีม

ในปัจจุบัน การจัดการโครงงานนักศึกษายังคงอาศัยไฟล์ Excel และเอกสารกระดาษในการจัดเก็บข้อมูล ติดตามความคืบหน้า และประเมินผล ซึ่งส่งผลให้กระบวนการดำเนินงานขาดความเป็นระบบ ล่าช้า และอาจก่อให้เกิดข้อผิดพลาดหรือความไม่สะดวกในการจัดเก็บและรวบรวมข้อมูล

## 👥 ผู้มีส่วนได้ส่วนเสีย

ระบบ SPDP รองรับการทำงานของ 3 กลุ่มผู้ใช้หลัก:

- **นักศึกษา** - สมาชิกโครงงานและผู้นำเสนอ
- **อาจารย์ที่ปรึกษา** - ผู้ให้คำแนะนำและติดตามความคืบหน้า
- **เจ้าหน้าที่คณะ** - ผู้ดูแลและจัดการระบบโดยรวม

## 🔄 ขั้นตอนกระบวนการ Senior Project

1. **การลงชื่อสมาชิกกลุ่มและอาจารย์ที่ปรึกษา**
2. **การกรอกรายละเอียดโครงงาน**
3. **การจัดสรรคณะกรรมการสำหรับการประเมิน**
4. **การลงคะแนนนักศึกษา**
5. **การจัดการเกรด**
6. **การเตรียมตารางเวลาสำหรับการนำเสนอโครงงาน**

## 🎯 วัตถุประสงค์

### 1. พัฒนาระบบจัดการโครงงานนักศึกษา
ช่วยลดขั้นตอนและเวลาทำงานของเจ้าหน้าที่ฝ่ายการศึกษา

### 2. ติดตามสถานะ Senior Project
อาจารย์ที่ปรึกษาและคณะกรรมการสามารถติดตามกระบวนการของ Senior Project ได้

### 3. จัดเก็บและบริหารข้อมูลโครงงาน
รวบรวมข้อมูลเกี่ยวกับโครงงานในฐานข้อมูลเพื่อให้สามารถค้นหาและเข้าถึงได้อย่างสะดวกและง่ายดาย

## 💡 ประโยชน์ที่ได้รับ

### ด้านผู้ใช้งานระบบ
- ช่วยลดภาระงานในด้านการจัดการเอกสาร
- สามารถเข้าถึงข้อมูลโครงงานได้อย่างรวดเร็ว

### ด้านสิ่งที่คณะสามารถนำไปต่อยอดได้
- สามารถวิเคราะห์ข้อมูลได้อย่างมีประสิทธิภาพ

### ด้านผู้พัฒนา
- พัฒนาทักษะการทำงานเป็นทีม
- พัฒนาระบบที่สามารถต่อยอดได้ในอนาคต

## 📱 คุณสมบัติหลัก

- **📝 การจัดการโครงงาน** - ลงทะเบียน แก้ไข และติดตามสถานะโครงงาน
- **👨‍🏫 ระบบอาจารย์ที่ปรึกษา** - จัดสรรและติดตามความคืบหน้า
- **📊 ระบบประเมินผล** - จัดสรรคณะกรรมการและบันทึกคะแนน
- **📅 ตารางการนำเสนอ** - จัดการเวลาและสถานที่นำเสนอ
- **📈 รายงานและสถิติ** - วิเคราะห์ข้อมูลและสร้างรายงาน


## 🏃🏻‍♀️ วิธีการ run Project 🏃🏻‍♀️

โปรเจกต์นี้เป็นแอปพลิเคชันที่พัฒนาด้วย [Spring Boot](https://spring.io/projects/spring-boot) พร้อมเชื่อมต่อกับฐานข้อมูล MySQL และใช้ฐานข้อมูลจากไฟล์ `Final_Database_SeniorProject.sql`

### 🔧 ความต้องการก่อนใช้งาน

ติดตั้งสิ่งต่อไปนี้ก่อนเริ่ม:

* Java 17 หรือสูงกว่า
* Maven
* Git
* MySQL 8.x
* IDE เช่น IntelliJ IDEA, VS Code หรืออื่น ๆ
  

#### 📥 ดาวน์โหลดไฟล์ฐานข้อมูล

สามารถดาวน์โหลดไฟล์ `Final_Database_SeniorProject.sql` ได้จาก [ที่นี่](https://github.com/TongTunyarat/SPDP-Project/blob/main/database/Final_Database_SeniorProject.sql)


### 🗄 การติดตั้ง MySQL

#### 1. ติดตั้ง MySQL

##### ▪️ สำหรับ Windows/macOS:

ดาวน์โหลดจาก: [https://dev.mysql.com/downloads/mysql/](https://dev.mysql.com/downloads/mysql/)


#### 2. สร้างฐานข้อมูลและผู้ใช้งาน

เข้าสู่ MySQL CLI:

```bash
mysql -u root -p
```

จากนั้นรันคำสั่งต่อไปนี้ใน MySQL:

```sql
CREATE DATABASE springbootdb;
CREATE USER 'springuser'@'localhost' IDENTIFIED BY 'springpass';
GRANT ALL PRIVILEGES ON springbootdb.* TO 'springuser'@'localhost';
FLUSH PRIVILEGES;
EXIT;
```


#### 3. สร้างโฟลเดอร์ `database` และนำเข้าไฟล์ฐานข้อมูล

1. สร้างโฟลเดอร์ `database`:

   * ให้สร้างโฟลเดอร์ใหม่ชื่อว่า `database` ใน path ที่ใช้งาน
   * นำไฟล์ `Final_Database_SeniorProject.sql` ไปไว้ในโฟลเดอร์ `database`

2. นำเข้าไฟล์ฐานข้อมูลไปยังฐานข้อมูล `springbootdb`:
   
> 💡 **คำแนะนำ**: ให้แน่ใจว่าไฟล์ `.sql` อยู่ในโฟลเดอร์ `database/` ของโปรเจกต์

##### ▪️ กรณีใช้ **PowerShell (Windows)**:

```powershell
Get-Content .\database\Final_Database_SeniorProject.sql | mysql -u springuser -p springbootdb
```

เมื่อระบบถามรหัสผ่าน ให้ใส่: `springpass`

##### ▪️ กรณีใช้ **Git Bash / Linux / macOS**:

```bash
mysql -u springuser -p springbootdb < database/Final_Database_SeniorProject.sql
```

##### ▪️ กรณีใช้ **MySQL Workbench** (GUI):

1. เปิด MySQL Workbench
2. เชื่อมต่อฐานข้อมูลโดยใช้ โดยสร้าง MySQL Connection ใหม่ ดังนี้ user: `springuser` password: `springpass` และ database: `springbootdb`
3. ไปที่ **Server > Data Import** แล้วเลือกไฟล์ `Final_Database_SeniorProject.sql` ที่ดาวน์โหลดมา
4. เลือก Default Target Schema เป็น springbootdb
5. กด Start Import


### 🚀 วิธีการติดตั้งและรันโปรเจกต์

#### 1. Clone โปรเจกต์

```bash
git clone https://github.com/TongTunyarat/SPDP-Project.git
```

#### 2. ตั้งค่าไฟล์ `application.properties`

1. หลังจาก clone โปรเจกต์เสร็จแล้ว ให้เปิดโปรเจกต์ใน IDE ที่คุณใช้งาน เช่น IntelliJ IDEA หรือ VS Code
2. จากนั้น เปิดไฟล์ `src/main/resources/application.properties`
3. แก้ไขการตั้งค่าดังนี้:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/springbootdb
spring.datasource.username=springuser
spring.datasource.password=springpass
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
```

#### 3. Build และ Run

##### ▪️ Maven:

* ในกรณีที่ใช้ IDE เช่น IntelliJ IDEA หรือ VS Code ให้กด "Run" จาก IDE ได้เลย
* ถ้าพบปัญหาเกี่ยวกับ Lombok annotations ให้ยอมรับการตั้งค่า "Enable annotation processing" ใน IDE ด้วย
* ในกรณีที่ใช้คำสั่งนี้ใน PowerShell / Git Bash / Terminal ใน IDE:

```bash
./mvnw spring-boot:run
```


### 🌐 การเข้าถึงระบบ

หลังจากรันแอปแล้ว ให้เข้าใช้งานได้ที่:

```
http://localhost:8080/login
```

---


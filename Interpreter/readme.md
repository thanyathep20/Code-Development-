# Interpreters
Interpreter คือ เป็นโปรแกรมคอมพิวเตอร์ที่ใช้ในการอ่านและประมวลผลโค้ดหรือสคริปต์ภาษาโปรแกรม โดยจะทำงานทีละคำสั่งหรือทีละบรรทัดตามลำดับที่กำหนดโดยโค้ด โดยไม่ต้องคอมไพล์ทั้งโปรแกรมก่อนที่จะรัน เป็นอุปกรณ์สำคัญในการทำให้โปรแกรมสามารถทำงานได้ตามคำสั่งที่กำหนดในโค้ดทันที Interpreter มักถูกใช้กับภาษาโปรแกรมที่ไม่ต้องคอมไพล์ก่อนการรัน เช่น Python, Perl, Ruby, JavaScript, Shell script, และภาษาโปรแกรมอื่น ๆ ที่มีลักษณะเป็นสคริปต์หรือสกีปต์ โดย Interpreter จะอ่านโค้ดทีละบรรทัด แปลงเป็นคำสั่งที่เครื่องคอมพิวเตอร์เข้าใจได้ และรันคำสั่งนั้นตามลำดับ
## Shell Interpreter
---
* Bash (Bourne-Again Shell) คือ เป็น Shell ที่พัฒนามาจาก Bourne Shell (sh) และเป็น Shell ที่ใช้งานได้กว้างขึ้นและมีความสามารถมากขึ้น มีการใช้งานที่แพร่หลายที่สุดในระบบปฏิบัติการ Unix และ Linux
* Zsh (Z Shell) คือ เป็น Shell ที่เพิ่มความสมบูรณ์และความสามารถในการใช้งานมากขึ้น มีฟีเจอร์ที่ล้ำสมัยมากกว่า Bash และมีระบบคอมเพล็กซ์ที่สามารถปรับแต่งได้มากขึ้น
* Ksh (Korn Shell) คือ เป็น Shell ที่ออกแบบมาเพื่อเป็นการรวมความสามารถทั้งหมดของ Bourne Shell (sh) และ C Shell (csh) โดยมีความสามารถในการทำงานและประสิทธิภาพที่ดี

### ความแตกต่างระหว่าง Bash และ Zsh 
---
ขอเริ่มต้นด้วยความเหมือนกันเนื่องจาก Bash และ Zshเป็น shell ที่สามารถใช้งานได้บนประบบปฏิบัติการ Unix และ Liinux โดยทั้ง 2 อย่างมีการทำงานเกี่ยวกับไฟล์และ โฟล์เดอร์ที่ กระบวนการจัดการ การตรวจสอบสิทธ์

ความแตกต่าง

* การเขียนคำสั่งและการแสดงผล โดยZshมีฟีเจอร์และการแสดงผลทันสมัยกว่าBash ทำให้Zshมีประสิทธิ์ภาพการและ สะดวกกว่าก่ารใช้งาน Bash
* ระบบcomplex Zsh จะมีระบบcomplex ที่สามารถปรับแต่งได้มากกว่าBash ทำให้ผู้ใช้สามารถปรับการทำงานของShell ได้ตามความเหมาะสมกับผู้ใช้ได้มากขึ้น
* ส่วนเสริม Zsh มีสิ่งที่เข้ามาช่วยคือส่วนเสริมหรือplugin เข้าไปช่วยในการทำงานของshell เพื่อเพื่มประสิทธิ์ภาพในการทำงานได้หลายหลายมากยิ่งขึ้น
## Programming Language Interpreter
--- 
Programming Languages Interpreter คือ ตัวแปลระบบสั่งภาษาโปรแกรม เป็นโปรแกรมคอมพิวเตอร์ที่ใช้ในการแปลและประมวลผลโค้ดหรือสคริปต์ของภาษาโปรแกรมต่าง ๆ โดยไม่ต้องคอมไพล์เป็นไฟล์เครื่องก่อนที่จะรัน มันทำหน้าที่แปลงโค้ดภาษาโปรแกรมเป็นคำสั่งที่เครื่องคอมพิวเตอร์เข้าใจและรันคำสั่งนั้นตามลำดับ
Interpreter อ่านโค้ดของโปรแกรมหรือสคริปต์ทีละบรรทัด แปลงเป็นคำสั่งที่เครื่องคอมพิวเตอร์เข้าใจได้ และรันคำสั่งนั้นตามลำดับ โดยไม่ต้องคอมไพล์ทั้งโปรแกรมก่อนที่จะรัน ประกอบด้วย
* Python Interpreter มีหน้าที่ในการอ่านโค้ด Python และแปลงเป็นภาษาเครื่อง หรือที่เรียกว่า (machine code) สามารถใช้ Python Interpreter ในโหมดแบบอินเทอร์แอคทีฟ (interactive mode) เพื่อรันคำสั่งหรือโค้ด Python ทันที หรือใช้ในโหมดที่อ่านและรันสคริปต์ Python จากไฟล์ (script mode)
นอกจากนี้ Python Interpreter ยังมีความสามารถในการจัดการกับตัวแปร การสร้างฟังก์ชัน การใช้คำสั่งเงื่อนไขและการทำซ้ำ
โดยปกติ Python Interpreter จะมาพร้อมกับการติดตั้ง Python บนเครื่องคอมพิวเตอร์ของคุณ และสามารถเรียกใช้งานผ่าน Command Line Interface (CLI) หรือผ่าน IDE (Integrated Development Environment) ต่าง ๆ ที่รองรับ Python อย่างได้เสรี เช่น IDLE, PyCharm, Jupyter Notebook 



* Perl Interpreter เป็นอินเทอร์เพอร์เตอร์ที่มีประสิทธิภาพและหลากหลายฟีเจอร์ มีความยืดหยุ่นและเป็นภาษาโปรแกรมที่มีประสิทธิภาพในการประมวลผลข้อมูลและสร้างสคริปต์ต่าง ๆ ในงานต่าง ๆ ได้และยังเป็นเครื่องมือที่มีความสามารถในการจัดการกับข้อยกเว้นและการจัดการกับข้อมูลชนิดต่าง ๆ ได้อย่างมีประสิทธิภาพ
การทำงานของ Perl Interpreter มักจะแบ่งเป็นสามขั้นตอนหลัก คือ

  1. การอ่านและแปลคำสั่ง: Perl Interpreter จะอ่านและแปลคำสั่งในภาษา Perl ทีละบรรทัดหรือทีละคำสั่ง เพื่อแปลงเป็นภาษาเครื่อง (machine code) ซึ่งเครื่องคอมพิวเตอร์สามารถทำงานได้

  2. การประมวลผล: เมื่อคำสั่งถูกแปลและแปลงเป็นภาษาเครื่องแล้ว Perl Interpreter จะทำงานตามลำดับของคำสั่งนั้น ๆ ตามที่ได้รับการระบุไว้ในโค้ด

  3. การผลลัพธ์: เมื่อการประมวลผลเสร็จสิ้น Perl Interpreter จะส่งผลลัพธ์ที่ได้กลับมาให้ผู้ใช้ ซึ่งอาจเป็นข้อความที่แสดงบนหน้าจอหรือการแสดงผลลัพธ์ทางไฟล์

* Ruby Interpreter: Ruby Interpreter เป็นโปรแกรมคอมพิวเตอร์ที่ใช้ในการรันภาษาโปรแกรม Ruby โดยมีหน้าที่แปลและประมวลผลโค้ดหรือสคริปต์ Ruby เพื่อให้เครื่องคอมพิวเตอร์เข้าใจและทำงานตามคำสั่งที่ได้รับโดยการทำงานของ Ruby Interpreter มักจะประกอบด้วยขั้นตอนต่าง ๆ ดังนี้

    1. การแปลและวิเคราะห์โค้ด: Ruby Interpreter จะอ่านและวิเคราะห์โค้ดหรือสคริปต์ Ruby เพื่อตรวจสอบความถูกต้องของโค้ด และแปลงเป็นโค้ดระดับสูง (high-level code) ที่เครื่องคอมพิวเตอร์เข้าใจได้

    2. การสร้างโครงสร้างข้อมูล: เมื่อโค้ดถูกแปลและวิเคราะห์แล้ว Ruby Interpreter จะสร้างโครงสร้างข้อมูลต่าง ๆ ภายในหน่วยความจำของเครื่องคอมพิวเตอร์ เพื่อจัดเก็บข้อมูลต่าง ๆ ที่ใช้ในการทำงาน

    3. การทำงาน: เมื่อโค้ดและโครงสร้างข้อมูลถูกสร้างขึ้นเรียบร้อยแล้ว Ruby Interpreter จะเริ่มทำงานตามลำดับของคำสั่งที่ถูกระบุในโค้ด โดยการประมวลผลโค้ดแต่ละบรรทัดหรือคำสั่งในลำดับที่ถูกต้อง

    4. การส่งผลลัพธ์: เมื่อการทำงานเสร็จสิ้นและโปรแกรมได้รับข้อมูลที่ต้องการ หรือประมวลผลเสร็จสิ้นแล้ว Ruby Interpreter จะส่งผลลัพธ์ที่ได้กลับมาให้ผู้ใช้ ซึ่งอาจเป็นข้อความที่แสดงบนหน้าจอหรือข้อมูลที่บันทึกไว้ในไฟล์
* Node.js Interpreter: Node.js Interpreter มีความสำคัญในการพัฒนาซอฟต์แวร์และการทำงานกับข้อมูลในด้านเว็บแอปพลิเคชัน มักถูกใช้เป็นส่วนหนึ่งของเซิร์ฟเวอร์ที่ใช้ในการรันโค้ด JavaScript ในฝั่งเซิร์ฟเวอร์ โดยจะมีการทำงานหลักๆดังนี้
    1. การแปลและวิเคราะห์โค้ด: Node.js Interpreter จะอ่านและวิเคราะห์โค้ด JavaScript เพื่อตรวจสอบความถูกต้องของโค้ด และแปลงเป็นโค้ดระดับสูงที่เครื่องคอมพิวเตอร์เข้าใจได้

    2. การสร้างโครงสร้างข้อมูล: เมื่อโค้ดถูกแปลและวิเคราะห์แล้ว Node.js Interpreter จะสร้างโครงสร้างข้อมูลต่าง ๆ ภายในหน่วยความจำของเครื่องคอมพิวเตอร์ เพื่อจัดเก็บข้อมูลต่าง ๆ ที่ใช้ในการทำงาน

    3. การทำงาน: เมื่อโค้ดและโครงสร้างข้อมูลถูกสร้างขึ้นเรียบร้อยแล้ว Node.js Interpreter จะเริ่มทำงานตามลำดับของคำสั่งที่ถูกระบุในโค้ด โดยการประมวลผลโค้ดแต่ละบรรทัดหรือคำสั่งในลำดับที่ถูกต้อง

    4. การส่งผลลัพธ์: เมื่อการทำงานเสร็จสิ้นและโปรแกรมได้รับข้อมูลที่ต้องการ หรือประมวลผลเสร็จสิ้นแล้ว Node.js Interpreter จะส่งผลลัพธ์ที่ได้กลับมาให้ผู้ใช้ ซึ่งอาจเป็นข้อความที่แสดงบนหน้าจอหรือข้อมูลที่บันทึกไว้ในไฟล์

---

## Reference
https://www.linode.com/docs/guides/intro-bash-shell-scripting/

https://refine.dev/blog/zsh-vs-bash/#using-bash-on-windows

https://developer.mozilla.org/en-US/docs/Web/JavaScript

https://www.python.org/

https://www.freecodecamp.org/news/compiled-versus-interpreted-languages/

https://www.educba.com/zsh-vs-bash/

https://ruby-doc.org/

https://www.perl.org/

https://www.geeksforgeeks.org/compiler-vs-interpreter-2/

https://medium.com/c0d1um/bash-commands-and-shell-script-%E0%B8%96%E0%B9%89%E0%B8%B2%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B8%A3%E0%B8%B9%E0%B9%89%E0%B8%8A%E0%B8%B5%E0%B8%A7%E0%B8%B4%E0%B8%95%E0%B8%88%E0%B8%B0%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2-3b38f3093aab
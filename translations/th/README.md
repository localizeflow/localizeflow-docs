# Localizeflow – คู่มือเริ่มต้นอย่างรวดเร็ว

#### สนับสนุนโดย [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](./README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)

> **ต้องการโคลนแบบโลคัลไหม?**

> รีโพสนี้มีการแปลมากกว่า 50 ภาษา ซึ่งจะทำให้ขนาดการดาวน์โหลดเพิ่มขึ้นอย่างมาก หากต้องการโคลนโดยไม่มีการแปล ให้ใช้ sparse checkout:
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> ซึ่งจะมอบทุกอย่างที่คุณต้องการเพื่อทำคอร์สให้เสร็จได้เร็วขึ้นมาก
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow จะแปลเอกสารของคุณโดยอัตโนมัติและเปิดคำร้องขอดึง (pull requests) ทุกครั้งที่ไฟล์ต้นทางมีการเปลี่ยนแปลง  
คู่มือนี้จะแสดงวิธีติดตั้ง GitHub App และรันการแปลครั้งแรกของคุณภายในเวลาไม่ถึง 2 นาที


> [!NOTE]
>
> ปัจจุบัน Localizeflow รองรับโปรเจกต์เอกสารที่อยู่บน GitHub  
> (ตัวอย่างเช่น: AI for Beginners และรีโพมาตรฐานโอเพนซอร์สส่วนใหญ่)  
>
> กำลังพัฒนาการรองรับเอกสารโมเดิร์นเฟรมเวิร์คอย่าง Astro, Docusaurus, และ Hugo อยู่ในขั้นตอนการพัฒนาอย่างต่อเนื่อง


---

## ลงชื่อเข้าใช้และติดตั้ง GitHub App

1. ไปที่ **[localizeflow.com](https://localizeflow.com/)**  
2. เลือก **เริ่มต้นโดยทดลองใช้ฟรี**  
   ![เลือกเริ่มต้นโดยทดลองใช้ฟรี](../../../../translated images/th/select-start-with-free-trial.6c2e287133ff9c8b.webp)  
3. เลือก **ลงชื่อเข้าใช้ด้วย GitHub**  
   ![ลงชื่อเข้าใช้ด้วย GitHub](../../../../translated images/th/select-sign-in-with-github.f2850ffdd49cc894.webp)  
4. ลงชื่อเข้าใช้ด้วยบัญชี GitHub ของคุณ  
   ![เข้าสู่ระบบ GitHub](../../../../translated images/th/github-login.02bbaee0270b292e.webp)  
5. เลือกบัญชีที่คุณต้องการติดตั้ง Localizeflow GitHub App — บัญชีส่วนตัวของคุณ หรือองค์กรที่คุณดูแล  
   ![เลือกบัญชี](../../../../translated images/th/select-which-account-to-use.7050f5ed0b773bb0.webp)  
6. เลือกรีโพที่คุณต้องการให้ Localizeflow เข้าถึง จากนั้นเลือก **บันทึก**  
   ![เลือกรีโพและบันทึก](../../../../translated images/th/select-repo-and-save.5a95ae288aefec6e.webp)  
7. คุณจะถูกเปลี่ยนเส้นทางไปยังหน้าแรกของ Localizeflow

> [!TIP]
> หากต้องการเพิ่มรีโพเพิ่มเติมภายหลัง ให้เลือกบัญชีของคุณที่ส่วนหัวแล้วเลือก **+ เพิ่มรีโพเพิ่มเติม**  
> ![เพิ่มรีโพเพิ่มเติม](../../../../translated images/th/add-more-repo.2ca5154473aaaafb.webp)

---

## เชื่อมต่อรีโพของคุณกับ Localizeflow

1. ที่หน้าแรกของ Localizeflow ให้เลือก **+ เชื่อมต่อรีโพ**  
   ![เลือกเชื่อมต่อรีโพ](../../../../translated images/th/select-connect-repos.8ac6f96f77dcc62c.webp)  
2. เลือกรีโพที่ได้ติดตั้งไว้หนึ่งรายการที่ต้องการเชื่อมต่อ แล้วเลือก **บันทึก**  
   ![เลือกรีโพ](../../../../translated images/th/select-repo.dce94db722b44cf3.webp)  
3. รีโพที่เชื่อมต่อของคุณจะปรากฏทั้งที่หน้าแรกและหน้ารายการรีโพ  
   ![รีโพที่เชื่อมต่อ](../../../../translated images/th/repo-connected.9e5c21ee789fdcaa.webp)  

---

## เริ่มการแปลอัตโนมัติ

1. เลือกรีโพที่คุณเพิ่งเชื่อมต่อ  
   ![เลือกรีโพ](../../../../translated images/th/select-repo-to-detail.55e53233531f8518.webp)  
2. ที่หน้ารายละเอียดรีโพ ให้เลือก **แก้ไข** ที่ด้านล่าง  
   ![เลือกแก้ไข](../../../../translated images/th/select-edit.225184c8c46d7001.webp)  
3. ตั้งค่าการแปลของคุณ — สาขาเป้าหมาย (ค่าเริ่มต้น: `main`), ภาษาเป้าหมาย, และภาษาต้นทาง (ค่าเริ่มต้น: `en`) จากนั้นเลือก **บันทึก**  
   ![ตั้งค่าการแปล](../../../../translated images/th/configuration.ab55d0f8bab5711b.webp)  
4. เลือก **เริ่มต้น & อัตโนมัติ**  
   Localizeflow จะเริ่มแปลเอกสารของคุณโดยอัตโนมัติและเปิดคำร้องขอดึงทุกครั้งที่ต้นทางเปลี่ยนแปลง  
   ![เริ่มต้น & อัตโนมัติ](../../../../translated images/th/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**ข้อจำกัดความรับผิดชอบ**:  
เอกสารนี้ได้รับการแปลโดยใช้บริการแปลภาษาด้วยปัญญาประดิษฐ์ [Co-op Translator](https://github.com/Azure/co-op-translator) แม้เราจะพยายามอย่างเต็มที่เพื่อความถูกต้อง แต่โปรดทราบว่าการแปลอัตโนมัติอาจมีข้อผิดพลาดหรือความไม่ถูกต้อง เอกสารต้นฉบับในภาษาต้นทางถือเป็นแหล่งข้อมูลที่ถูกต้องตามหลักเกณฑ์ สำหรับข้อมูลที่สำคัญ ควรใช้บริการแปลโดยผู้เชี่ยวชาญด้านภาษามนุษย์ เราไม่รับผิดชอบต่อความเข้าใจผิดหรือการตีความที่เกิดขึ้นจากการใช้การแปลนี้
<!-- CO-OP TRANSLATOR DISCLAIMER END -->
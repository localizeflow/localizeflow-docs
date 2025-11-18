<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "77ebb90e250875dd305c1707a9d0434e",
  "translation_date": "2025-11-18T10:48:44+00:00",
  "source_file": "README.md",
  "language_code": "th"
}
-->
# Localizeflow – คู่มือเริ่มต้นอย่างรวดเร็ว

#### สนับสนุนโดย [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../br/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Thai](./README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](../vi/README.md)
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow จะแปลเอกสารของคุณโดยอัตโนมัติและเปิดคำขอดึง (pull requests) ทุกครั้งที่ไฟล์ต้นทางมีการเปลี่ยนแปลง  
คู่มือนี้จะแสดงวิธีการติดตั้งแอป GitHub และรันการแปลครั้งแรกของคุณภายในเวลาไม่ถึง 2 นาที


> [!NOTE]
>
> Localizeflow รองรับโครงการเอกสารที่ใช้ GitHub ในปัจจุบัน  
> (เช่น: AI for Beginners และรีโปมาตรฐานโอเพนซอร์สส่วนใหญ่)  
> 
> การสนับสนุนสำหรับเฟรมเวิร์กเอกสารสมัยใหม่ เช่น Astro, Docusaurus และ Hugo  
> กำลังอยู่ในระหว่างการพัฒนาอย่างต่อเนื่อง


---

## ลงชื่อเข้าใช้และติดตั้งแอป GitHub

1. เยี่ยมชม **[localizeflow.com](https://localizeflow.com/)**  
2. เลือก **เริ่มต้นด้วยทดลองใช้ฟรี**  
   ![Select Start with free trial](/images/select-start-with-free-trial.png)
3. เลือก **ลงชื่อเข้าใช้ด้วย GitHub**  
   ![Sign in with GitHub](/images/select-sign-in-with-github.png)
4. ลงชื่อเข้าใช้ด้วยบัญชี GitHub ของคุณ  
   ![GitHub login](/images/github-login.png)
5. เลือกบัญชีที่คุณต้องการติดตั้งแอป Localizeflow GitHub — บัญชีส่วนตัวของคุณหรือองค์กรที่คุณดูแล  
   ![Select account](/images/select-which-account-to-use.png)
6. เลือกรีโปที่คุณต้องการให้ Localizeflow เข้าถึง จากนั้นเลือก **บันทึก**  
   ![Select repo and save](/images/select-repo-and-save.png)
7. คุณจะถูกเปลี่ยนเส้นทางไปยังหน้าแรกของ Localizeflow

> [!TIP]
> หากต้องการเพิ่มรีโปเพิ่มเติมในภายหลัง ให้เลือกบัญชีของคุณที่ส่วนหัวแล้วเลือก **+ เพิ่มรีโปเพิ่มเติม**  
> ![Add more repositories](/images/add-more-repo.png)

---

## เชื่อมต่อรีโปของคุณกับ Localizeflow

1. ที่หน้าแรกของ Localizeflow เลือก **+ เชื่อมต่อรีโป**  
   ![Select connect repositories](/images/select-connect-repos.png)

2. เลือกหนึ่งในรีโปที่ติดตั้งแล้วที่คุณต้องการเชื่อมต่อ จากนั้นเลือก **บันทึก**  
   ![Select repository](/images/select-repo.png)

3. รีโปที่เชื่อมต่อของคุณจะแสดงบนทั้งหน้าแรกและหน้ารายการรีโป  
   ![Connected repositories](/images/repo-connected.png)

---

## เริ่มการแปลอัตโนมัติ

1. เลือกรีโปที่คุณเพิ่งเชื่อมต่อ  
   ![Select repository](/images/select-repo-to-detail.png)

2. ที่หน้ารายละเอียดรีโป เลือก **แก้ไข** ที่ด้านล่าง  
   ![Select edit](/images/select-edit.png)

3. กำหนดค่าการตั้งค่าการแปลของคุณ — สาขาเป้าหมาย (ค่าเริ่มต้น: `main`), ภาษาที่ต้องการแปล และภาษาต้นทาง (ค่าเริ่มต้น: `en`) จากนั้นเลือก **บันทึก**  
   ![Configure translation settings](/images/configuration.png)

4. เลือก **เริ่ม & อัตโนมัติ**  
   Localizeflow จะเริ่มแปลเอกสารของคุณโดยอัตโนมัติและเปิดคำขอดึงทุกครั้งที่ต้นทางมีการเปลี่ยนแปลง  
   ![Start & Automate](/images/select-automate.png)
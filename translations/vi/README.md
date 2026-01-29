# Localizeflow – Hướng Dẫn Bắt Đầu Nhanh

#### Được hỗ trợ bởi [Localizeflow](https://localizeflow.com/)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Arabic](../ar/README.md) | [Bengali](../bn/README.md) | [Bulgarian](../bg/README.md) | [Burmese (Myanmar)](../my/README.md) | [Chinese (Simplified)](../zh-CN/README.md) | [Chinese (Traditional, Hong Kong)](../zh-HK/README.md) | [Chinese (Traditional, Macau)](../zh-MO/README.md) | [Chinese (Traditional, Taiwan)](../zh-TW/README.md) | [Croatian](../hr/README.md) | [Czech](../cs/README.md) | [Danish](../da/README.md) | [Dutch](../nl/README.md) | [Estonian](../et/README.md) | [Finnish](../fi/README.md) | [French](../fr/README.md) | [German](../de/README.md) | [Greek](../el/README.md) | [Hebrew](../he/README.md) | [Hindi](../hi/README.md) | [Hungarian](../hu/README.md) | [Indonesian](../id/README.md) | [Italian](../it/README.md) | [Japanese](../ja/README.md) | [Kannada](../kn/README.md) | [Korean](../ko/README.md) | [Lithuanian](../lt/README.md) | [Malay](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Nigerian Pidgin](../pcm/README.md) | [Norwegian](../no/README.md) | [Persian (Farsi)](../fa/README.md) | [Polish](../pl/README.md) | [Portuguese (Brazil)](../pt-BR/README.md) | [Portuguese (Portugal)](../pt-PT/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Romanian](../ro/README.md) | [Russian](../ru/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Slovak](../sk/README.md) | [Slovenian](../sl/README.md) | [Spanish](../es/README.md) | [Swahili](../sw/README.md) | [Swedish](../sv/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugu](../te/README.md) | [Thai](../th/README.md) | [Turkish](../tr/README.md) | [Ukrainian](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamese](./README.md)

> **Ưu tiên Clone về máy?**

> Kho lưu trữ này bao gồm hơn 50 bản dịch ngôn ngữ, điều này làm tăng đáng kể kích thước tải xuống. Để clone mà không có bản dịch, hãy sử dụng sparse checkout:  
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/localizeflow-docs.git
> cd localizeflow-docs
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Điều này cung cấp cho bạn mọi thứ bạn cần để hoàn thành khóa học với thời gian tải xuống nhanh hơn nhiều.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

Localizeflow tự động dịch tài liệu của bạn và mở các pull request bất cứ khi nào file nguồn thay đổi.  
Hướng dẫn này sẽ chỉ cho bạn cách cài đặt Ứng dụng GitHub và chạy bản dịch đầu tiên của bạn trong chưa đầy 2 phút.


> [!NOTE]
>
> Hiện tại Localizeflow hỗ trợ các dự án tài liệu dựa trên GitHub  
> (ví dụ: AI cho Người mới bắt đầu và hầu hết các kho mã nguồn mở tiêu chuẩn).  
> 
> Hỗ trợ các framework tài liệu hiện đại như Astro, Docusaurus và Hugo  
> đang trong quá trình phát triển tích cực.


---

## Đăng nhập và cài đặt Ứng dụng GitHub

1. Truy cập **[localizeflow.com](https://localizeflow.com/)**.
2. Chọn **Bắt đầu với bản dùng thử miễn phí**.  
   ![Select Start with free trial](../../../../translated images/vi/select-start-with-free-trial.6c2e287133ff9c8b.webp)
3. Chọn **Đăng nhập với GitHub**.  
   ![Sign in with GitHub](../../../../translated images/vi/select-sign-in-with-github.f2850ffdd49cc894.webp)
4. Đăng nhập bằng tài khoản GitHub của bạn.  
   ![GitHub login](../../../../translated images/vi/github-login.02bbaee0270b292e.webp)
5. Chọn tài khoản mà bạn muốn cài đặt Ứng dụng Localizeflow GitHub — tài khoản cá nhân hoặc tổ chức mà bạn quản lý.  
   ![Select account](../../../../translated images/vi/select-which-account-to-use.7050f5ed0b773bb0.webp)
6. Chọn các kho bạn muốn Localizeflow truy cập, sau đó chọn **Lưu**.  
   ![Select repo and save](../../../../translated images/vi/select-repo-and-save.5a95ae288aefec6e.webp)
7. Bạn sẽ được chuyển hướng về trang chủ Localizeflow.

> [!TIP]
> Để thêm các kho lưu trữ sau này, hãy chọn tài khoản của bạn ở thanh đầu trang và chọn **+ Thêm kho lưu trữ**.  
> ![Add more repositories](../../../../translated images/vi/add-more-repo.2ca5154473aaaafb.webp)

---

## Kết nối kho lưu trữ của bạn với Localizeflow

1. Trên trang chủ Localizeflow, chọn **+ Kết nối kho lưu trữ**.  
   ![Select connect repositories](../../../../translated images/vi/select-connect-repos.8ac6f96f77dcc62c.webp)

2. Chọn một trong các kho được cài đặt mà bạn muốn kết nối và chọn **Lưu**.  
   ![Select repository](../../../../translated images/vi/select-repo.dce94db722b44cf3.webp)

3. Các kho được kết nối của bạn sẽ xuất hiện trên cả trang Chủ và trang Kho lưu trữ.  
   ![Connected repositories](../../../../translated images/vi/repo-connected.9e5c21ee789fdcaa.webp)

---

## Bắt đầu dịch tự động

1. Chọn kho lưu trữ bạn vừa kết nối.  
   ![Select repository](../../../../translated images/vi/select-repo-to-detail.55e53233531f8518.webp)

2. Trên trang chi tiết kho lưu trữ, chọn **Chỉnh sửa** ở dưới cùng.  
   ![Select edit](../../../../translated images/vi/select-edit.225184c8c46d7001.webp)

3. Cấu hình cài đặt dịch của bạn — nhánh đích (mặc định: `main`), ngôn ngữ đích, và ngôn ngữ nguồn (mặc định: `en`). Chọn **Lưu**.  
   ![Configure translation settings](../../../../translated images/vi/configuration.ab55d0f8bab5711b.webp)

4. Chọn **Bắt đầu & Tự động hóa**.  
   Localizeflow sẽ tự động dịch tài liệu của bạn và mở pull request bất cứ khi nào nguồn thay đổi.  
   ![Start & Automate](../../../../translated images/vi/select-automate.ff50c8d913b35a03.webp)

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Tuyên bố từ chối trách nhiệm**:  
Tài liệu này đã được dịch bằng dịch vụ dịch thuật AI [Co-op Translator](https://github.com/Azure/co-op-translator). Mặc dù chúng tôi cố gắng đảm bảo độ chính xác, xin lưu ý rằng các bản dịch tự động có thể chứa lỗi hoặc không chính xác. Văn bản gốc bằng ngôn ngữ gốc nên được coi là nguồn chính xác và đáng tin cậy. Đối với thông tin quan trọng, nên sử dụng bản dịch do người dịch chuyên nghiệp thực hiện. Chúng tôi không chịu trách nhiệm về bất kỳ sự hiểu lầm hoặc giải thích sai nào phát sinh từ việc sử dụng bản dịch này.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->

# 🧠 AI Prompt Studio (Web Version)

**AI Prompt Studio** là một ứng dụng web giao diện đơn, giúp bạn tạo, tối ưu hóa và chỉnh sửa prompt để tương tác với các mô hình AI hiện đại như **OpenAI GPT-4o** và **Google Gemini 1.5 Flash**. Ứng dụng hỗ trợ markdown, LaTeX, image input và tùy chỉnh nhiều loại ngữ cảnh sử dụng.

---

## 🚀 Tính năng nổi bật

- 🧠 Tương thích GPT-4o và Gemini 1.5
- 📌 Giao diện 3 cột trực quan: Input → Task → Output
- ✍️ Tùy chọn chi tiết: tone, vai trò, ngành nghề, kênh giao tiếp, ngôn ngữ, độ dài, v.v.
- 📎 Hỗ trợ đính kèm ảnh (image prompt) để phân tích hoặc mô tả ảnh
- 🧩 Quản lý biến tùy chỉnh (custom context variables)
- 💾 Lưu cấu hình người dùng (localStorage)
- 🔈 Đọc to kết quả đầu ra (text-to-speech)
- 🌙 Hỗ trợ Dark Mode
- 📄 Hướng dẫn nhanh và ví dụ prompt mẫu

---

## 🛠️ Cài đặt & Sử dụng

### 1. Clone hoặc tải project


### 2. Mở file HTML trong trình duyệt

```bash
# Cách 1: Mở trực tiếp trên macOS hoặc Linux
open Aipromptstudio.html
```

Hoặc kéo file `Aipromptstudio.html` vào trình duyệt bất kỳ (Chrome, Edge, Firefox, Safari...).

---

### 3. Thiết lập API Key

Mở file `Aipromptstudio.html` bằng trình soạn thảo mã nguồn (VSCode, Sublime, Notepad++...), và tìm đến đoạn:

```js
const OPENAI_API_KEY = "INSERT_YOUR_OPENAI_API_HERE";
const GEMINI_API_KEY = "INSERT_YOUR_GEMINI_API_HERE";
```

Thay thế bằng khóa API của bạn:

- 🔑 OpenAI API Key: [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)
- 🔑 Google Gemini API Key: [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)

> ⚠️ **Cảnh báo:** Không commit khóa API lên GitHub công khai. Hãy sử dụng biến môi trường hoặc backend để bảo mật nếu deploy online.

---

## 💡 Ví dụ sử dụng

### 📌 Prompt cải thiện văn phong

- **Input:** `The report is good. I need more time.`
- **Task:** Improve Text  
- **Tone:** Professional  
- **Recipient:** Superior/Manager  
- **Output:** Một email chuyên nghiệp đề nghị thêm thời gian với tiêu đề và nội dung rõ ràng.

### 🌐 Prompt dịch văn bản

- **Input:** `Hôm nay trời đẹp quá!`  
- **Task:** Translate Text  
- **Language:** English  
- **Output:** `The weather is so beautiful today!`

---

## 📋 Các task được hỗ trợ

- Improve Text
- Rewrite Text
- Change Tone
- Correct Grammar (minimal changes)
- Summarize
- Expand on Text/Idea
- Translate
- Dictionary
- English Learning
- Free Prompt

---

## 📦 Công nghệ sử dụng

- [TailwindCSS](https://cdn.tailwindcss.com)
- [Font Awesome](https://cdnjs.com)
- [marked.js](https://cdn.jsdelivr.net/npm/marked)
- [MathJax](https://cdn.jsdelivr.net/npm/mathjax)

Tất cả được import trực tiếp từ CDN — không cần cài đặt backend hay thư viện ngoài.

---

## 📄 Giấy phép

Phát hành theo [MIT License](LICENSE).

Phát triển bởi **Minh Do - 2025**


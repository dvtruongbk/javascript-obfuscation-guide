---
layout: default
title: Bắt đầu nhanh
nav_order: 2
---

# Bắt đầu nhanh

## Yêu cầu

- Node.js (phiên bản 14 trở lên)
- npm hoặc yarn
- Trình soạn thảo code (VS Code, Sublime Text, etc.)

## Cài đặt

1. Clone repository:
```bash
git clone https://github.com/[username]/javascript-obfuscation-guide.git
cd javascript-obfuscation-guide
```

2. Cài đặt dependencies:
```bash
npm install
```

## Cấu trúc dự án

```
javascript-obfuscation-guide/
├── docs/                    # Thư mục chứa tài liệu
│   ├── _config.yml         # Cấu hình Jekyll
│   ├── index.md            # Trang chủ
│   ├── getting-started.md  # Hướng dẫn bắt đầu
│   └── images/             # Thư mục chứa hình ảnh
└── examples/               # Thư mục chứa ví dụ
    ├── basic/             # Ví dụ cơ bản
    └── advanced/          # Ví dụ nâng cao
```

## Các bước cơ bản

1. **Chuẩn bị code**
   - Kiểm tra code hoạt động
   - Loại bỏ comment không cần thiết
   - Tối ưu hóa code

2. **Obfuscate code**
   - Sử dụng JavaScript Obfuscator
   - Cấu hình các tùy chọn
   - Kiểm tra kết quả

3. **Kiểm thử**
   - Chạy thử code đã obfuscate
   - Kiểm tra các tính năng
   - Tối ưu hóa nếu cần

## Ví dụ nhanh

```javascript
// Code gốc
function hello(name) {
    console.log("Hello, " + name);
}

// Code sau khi obfuscate
function _0x1a2b(_0x3c4d,_0x5e6f){return _0x3c4d+_0x5e6f;}
```

## Tiếp theo

- [Hướng dẫn chi tiết](/guide)
- [Ví dụ thực tế](/examples)
- [Tài liệu tham khảo](/references) 
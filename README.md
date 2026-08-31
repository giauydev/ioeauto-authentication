# IOEAuto Authentication

Ứng dụng xác thực mở rộng dành cho **IOEAuto Plus**, hỗ trợ nhiều phương thức đăng nhập:

* 🔵 Google Login
* 🔷 Facebook Login
* 🟢 Native IOE Login

> **Developed by giauydev**

## 📦 Yêu cầu

Ứng dụng yêu cầu **Microsoft Edge WebView2 Runtime** để hoạt động.

👉 **[Tải Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/)**

**Hệ Điều Hành:** Windows 7, 8, 10, 11
**Khuyến nghị:** Windows 10/11

### Kiểm tra nhanh WebView2 Runtime đã được cài đặt chưa

Mở **CMD (Command Prompt/Terminal/Windows PowerShell)** và chạy:

```cmd
reg query "HKLM\SOFTWARE\WOW6432Node\Microsoft\EdgeUpdate\Clients" /s /f "WebView2"
```

Nếu WebView2 đã được cài đặt, kết quả trả về của cmd sẽ trông như thế này:

```text
HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Microsoft\EdgeUpdate\Clients\{F3xxxx26-FE2A-4295-xxxx-xxxxxxxxxx}
    name    REG_SZ    Microsoft Edge WebView2 Runtime

End of search: 1 match(es) found.
```

Khi thấy dòng:

```text
name    REG_SZ    Microsoft Edge WebView2 Runtime
```

→ **WebView2 Runtime đã được cài đặt.**

Nếu không tìm thấy kết quả, hãy cài đặt WebView2 Runtime từ trang Microsoft ở trên trước khi chạy ứng dụng.

## 🏠 Cài đặt

1. Cài đặt **WebView2 Runtime** nếu máy chưa có.
2. Tải phiên bản **IOEAuto Authentication** mới nhất tại **[GitHub Releases](https://github.com/giauydev/ioeauto-authentication/releases)**.
3. Chạy ứng dụng lần đầu.

> **Lưu ý:** Chỉ cần mở ứng dụng một lần duy nhất. Nếu bạn di chuyển ứng dụng sang đường dẫn khác, hãy mở ứng dụng một lần nữa.

## 🚀 Sử dụng

Sử dụng phương thức đăng nhập khác trên **[IOEAuto Plus](https://ioeauto.giauy.dev/plus-main)** để sử dụng.

## 📄 License

**Proprietary Software — All Rights Reserved**

© 2026 IOEAuto by giauydev. All Rights Reserved

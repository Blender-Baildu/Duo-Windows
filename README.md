# Windows 11 on GitHub Actions

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/blender-baildu/duo-windows/windows11.yml?branch=main)
![License](https://img.shields.io/github/license/blender-baildu/duo-windows)

> Triển khai máy ảo Windows 11 trên GitHub Actions với Ngrok TCP và KVM hỗ trợ VT-x.

---

## ⚙️ Tính năng

- **Windows 11 Lite** (file `.qcow2` tinh chỉnh sẵn).
- **Tùy chỉnh RAM:** 4GB, 8GB, 12GB hoặc 16GB.
- **Ổ cứng SSD 80GB**.
- **2 vCPU Core**.
- **Ngrok Tunnel**: kết nối RDP (Remote Desktop) dễ dàng.
- **Giới hạn CPU** để ổn định hệ thống.

---

## 🚀 Cách sử dụng

1. **Fork** dự án này.
2. Vào mục **Actions** → chọn **`W11`** workflow.
3. Điền:
   - Ngrok Auth Token (`ngrok`).
   - Số RAM mong muốn (`ram`).
4. Bấm **Run workflow**.

Bạn sẽ nhận được **IP và Port** để kết nối RDP qua Remote Desktop Client.

---

## 🔐 Điều khoản sử dụng

- File `.qcow2` sử dụng **Windows Evaluation Version** hoặc bản được phép chỉnh sửa cá nhân.
- Không lưu trữ hoặc phân phối phần mềm vi phạm bản quyền.
- Tôn trọng [GitHub Actions usage policies](https://docs.github.com/en/actions/using-github-hosted-runners/about-github-hosted-runners).

---

## 📄 License

Dự án này được cấp phép theo giấy phép **MIT License**.  
Xem thêm tại file [`LICENSE`](./LICENSE).

---

## 🖼️ Hình ảnh minh họa

| Trước | Sau |
|:-----:|:---:|
| ![loading](https://img.icons8.com/fluency/48/windows11.png) | ![ready](https://img.icons8.com/fluency/48/connected.png) |

---

> Made with ❤️ by [blender-baildu](https://github.com/blender-baildu)

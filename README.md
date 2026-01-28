<div align="center">
<div align="center">

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wuy2team&layout=compact&theme=github_dark&hide=html,css" />
</div>


</div>

<img src="https://capsule-render.vercel.app/api?type=rect&height=110&text=H%C3%A0%20%C4%90%E1%BB%A9c%20Huy&fontSize=40&fontAlignY=60&color=0:020617,100:111827&fontColor=ffffff" />

<br/>

<a href="https://huyductech.id.vn">
  <img src="https://img.shields.io/badge/WEBSITE-111827?style=for-the-badge&logo=githubpages&logoColor=white" />
</a>
<a href="https://www.facebook.com/hellohuyduc">
  <img src="https://img.shields.io/badge/FACEBOOK-111827?style=for-the-badge&logo=facebook&logoColor=white" />
</a>
<a href="https://github.com/wuy2team">
  <img src="https://img.shields.io/badge/GITHUB-111827?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/><br/>

<b>Sinh viên Công nghệ thông tin</b>  
Định hướng <b>ASP.NET Core MVC – Web Bán Hàng – Hệ Thống Quản Trị</b>

<br/>
Tư duy nghiệp vụ • Kiến trúc rõ ràng • Làm sản phẩm dùng được thật

</div>

---

## 👋 Giới thiệu
Mình là **Hà Đức Huy** – sinh viên CNTT, định hướng phát triển **hệ thống web bán hàng hoàn chỉnh** bằng **ASP.NET Core MVC**.

Mình tập trung vào:
- **Nghiệp vụ thương mại thực tế** (sản phẩm, đơn hàng, tồn kho, thanh toán)
- **Quản trị hệ thống** (admin, phân quyền, thống kê)
- **Kiến trúc rõ ràng** (MVC, Service, Repository)
- Code theo hướng **dễ mở rộng – dễ bảo trì – đúng chuẩn doanh nghiệp**

Không làm demo đơn giản. Mục tiêu là **một hệ thống có thể đưa vào vận hành**.

---

## 🎯 Mục tiêu hiện tại
- Hoàn thiện **Website Bán Hàng ASP.NET Core MVC – Full chức năng**
- Chuẩn hoá nghiệp vụ: **đơn hàng – kho – giá – người dùng**
- Áp dụng **Entity Framework Core + SQL Server**
- Nâng cao trải nghiệm người dùng & hiệu năng

---

## ⭐ Dự án chính
### 🛒 HỆ THỐNG WEB BÁN HÀNG – ASP.NET CORE MVC
**Mục tiêu:**  
Xây dựng hệ thống bán hàng online đầy đủ chức năng cho doanh nghiệp nhỏ & vừa.

---

### 🧱 Công nghệ sử dụng
- **Backend:** ASP.NET Core MVC (.NET 6 / .NET 8)
- **ORM:** Entity Framework Core
- **Database:** SQL Server
- **Frontend:** Razor View, Bootstrap, JavaScript
- **Authentication:** ASP.NET Core Identity
- **Architecture:** MVC + Service + Repository

---

### 🧩 Chức năng khách hàng
- Đăng ký / đăng nhập / quên mật khẩu
- Danh sách sản phẩm (phân trang, tìm kiếm, lọc)
- Sản phẩm có **biến thể** (size, màu, giá riêng)
- Giỏ hàng (AJAX)
- Đặt hàng & theo dõi trạng thái đơn
- Áp dụng mã giảm giá (Voucher)
- Lịch sử mua hàng
- Đánh giá sản phẩm

---

### 🧑‍💼 Chức năng Admin
- Dashboard thống kê:
  - Doanh thu
  - Số đơn hàng
  - Sản phẩm bán chạy
- Quản lý sản phẩm:
  - CRUD
  - Ảnh sản phẩm
  - Biến thể
- Quản lý danh mục
- Quản lý đơn hàng:
  - Xác nhận
  - Đang giao
  - Hoàn thành
  - Huỷ
- Quản lý người dùng & phân quyền
- Quản lý tồn kho (theo phiếu nhập)
- Quản lý voucher / khuyến mãi

---

### 🧮 Nghiệp vụ chuẩn
- **Giá vốn ≠ Giá bán**
- **Tồn kho lấy từ phiếu nhập**
- **Snapshot giá tại thời điểm đặt hàng**
- Không thay đổi dữ liệu lịch sử
- Đảm bảo **tính nhất quán kế toán**

---

## 🧱 Kiến trúc dự án
```text
/Controllers
/Areas
  /Admin
    /Controllers
/Models
/Data
/Services
/Repositories
/ViewModels
/Views
/wwwroot

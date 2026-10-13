# Chapter_2_GioiThieu_ASP_Net_WebForm

> **Nguồn tài liệu**: Chapter_2_GioiThieu_ASP_Net_WebForm.pdf
> **Tổng số trang**: 43

## Mục lục nhanh

- [Trang 1: ThS. TRẦN KIM HƯƠNG – KHOA CÔNG NGHỆ SỐ VÀ KỸ THUẬT](#trang-1)
- [Trang 2: Bài giảng Lập trình web aspx](#trang-2)
- [Trang 3: Bài giảng Lập trình web aspx](#trang-3)
- [Trang 4: Bài giảng Lập trình web aspx](#trang-4)
- [Trang 5: Bài giảng Lập trình web aspx](#trang-5)
- [Trang 6: Bài giảng Lập trình web aspx](#trang-6)
- [Trang 7: Bài giảng Lập trình web aspx](#trang-7)
- [Trang 8: Bài giảng Lập trình web aspx](#trang-8)
- [Trang 9: Bài giảng Lập trình web aspx](#trang-9)
- [Trang 10: Bài giảng Lập trình web aspx](#trang-10)
- [Trang 11: Bài giảng Lập trình web aspx](#trang-11)
- [Trang 12: Bài giảng Lập trình web aspx](#trang-12)
- [Trang 13: Bài giảng Lập trình web aspx](#trang-13)
- [Trang 14: Bài giảng Lập trình web aspx](#trang-14)
- [Trang 15: Bài giảng Lập trình web aspx](#trang-15)
- [Trang 16: Bài giảng Lập trình web aspx](#trang-16)
- [Trang 17: Bài giảng Lập trình web aspx](#trang-17)
- [Trang 18: Bài giảng Lập trình web aspx](#trang-18)
- [Trang 19: Bài giảng Lập trình web aspx](#trang-19)
- [Trang 20: Bài giảng Lập trình web aspx](#trang-20)
- [Trang 21: Bài giảng Lập trình web aspx](#trang-21)
- [Trang 22: Bài giảng Lập trình web aspx](#trang-22)
- [Trang 23: Bài giảng Lập trình web aspx](#trang-23)
- [Trang 24: Bài giảng Lập trình web aspx](#trang-24)
- [Trang 25: Bài giảng Lập trình web aspx](#trang-25)
- [Trang 26: Bài giảng Lập trình web aspx](#trang-26)
- [Trang 27: Bài giảng Lập trình web aspx](#trang-27)
- [Trang 28: Bài giảng Lập trình web aspx](#trang-28)
- [Trang 29: Bài giảng Lập trình web aspx](#trang-29)
- [Trang 30: Bài giảng Lập trình web aspx](#trang-30)
- [Trang 31: Bài giảng Lập trình web aspx](#trang-31)
- [Trang 32: Bài giảng Lập trình web aspx](#trang-32)
- [Trang 33: Bài giảng Lập trình web aspx](#trang-33)
- [Trang 34: Bài giảng Lập trình web aspx](#trang-34)
- [Trang 35: Bài giảng Lập trình web aspx](#trang-35)
- [Trang 36: Bài giảng Lập trình web aspx](#trang-36)
- [Trang 37: Bài giảng Lập trình web aspx](#trang-37)
- [Trang 38: Bài giảng Lập trình web aspx](#trang-38)
- [Trang 39: Bài giảng Lập trình web aspx](#trang-39)
- [Trang 40: Bài giảng Lập trình web aspx](#trang-40)
- [Trang 41: Bài giảng Lập trình web aspx](#trang-41)
- [Trang 42: Bài giảng Lập trình web aspx](#trang-42)
- [Trang 43: tkhuong@dthu.edu.vn](#trang-43)

---

## Trang 1

ThS. TRẦN KIM HƯƠNG – KHOA CÔNG NGHỆ SỐ VÀ KỸ THUẬT
tkhuong@dthu.edu.vn
GIỚI THIỆU ASP.NET & 
WEB FORM

---

## Trang 2

Bài giảng Lập trình web aspx
NỘI DUNG
3
tkhuong@dthu.edu.vn
Giới thiệu ASP.NET
Các điểm nổi bật của Asp.Net
Giới thiệu .NET Framework
Các mô hình phát triển ứng dụng ASP.NET
Các thành phần ứng dụng ASP.NET
Cơ chế xử lý ứng dụng ASP.NET
Giới thiệu ASP.NET Web Form

---

## Trang 3

Bài giảng Lập trình web aspx
1. Giới thiệu ASP.NET
❖ASP.Net là Active Server Page .NET
❖Là công nghệ của Microsoft cho phép xd các ứng dụng 
web động
❖Là kỹ thuật lập trình và phát triển ứng dụng web ở phía 
Server (server-side) dựa trên trên nền tảng .NET 
Framework
▪Với kỹ thuật server-side, các đoạn code được xử lý tại 
server và phát sinh ra HTML, Javascript, CSS sau đó gửi 
về cho trình duyệt ở phía Client.
❖Được phát triển từ ASP
▪.asp vs .aspx
4
GV biên soạn: Trần Kim Hương

---

## Trang 4

Bài giảng Lập trình web aspx
Web tĩnh vs Web động
❖Nhắc lại Quy trình phát triển phần mềm (web nói 
riêng)???
▪Phân tích yc > Thiết kế (design) > Cài đặt (coding) > Kiểm 
thử (testing) > Triển khai (hosting)
❖VD: Thiết kế website giới thiệu nhóm
▪1 trang chủ
• Logo + slogan
• Liệt kê danh sách các thành viên trong nhóm
▪Mỗi thành viên liên kết đến trang cá nhân
• Họ tên, Email, Hình cá nhân, Thông tin khác (nếu có)
5
GV biên soạn: Trần Kim Hương

---

## Trang 5

Bài giảng Lập trình web aspx
Web tĩnh vs Web động
❖Web tĩnh
▪Thêm thành viên mới ?????
▪→ muốn thay đổi nội dung, ltr viên phải thực hiện lại quy trình phát triển 
web
6
GV biên soạn: Trần Kim Hương
Homepage
Default.html
Member 1
Member1.html
Member 2
Member2.html
……..

---

## Trang 6

Bài giảng Lập trình web aspx
Web tĩnh vs Web động
❖Web động
▪Thêm thành viên mới → vào CSDL thêm or có chức năng trên web để 
thêm vào CSDL
7
GV biên soạn: Trần Kim Hương
Homepage
Default.aspx
Member i
Member.aspx
……..
CSDL
Members:
- member1
- member2
……

---

## Trang 7

Bài giảng Lập trình web aspx
2. Các điểm nổi bật của ASP.NET
❖Hỗ trợ đa ngôn ngữ: C#, VB.NET, JScript.NET
❖Biên dịch trước các trang và cơ chế Caching giúp làm 
tăng tốc độ thực hiện
❖Môi trường phát triển tích hợp, dễ dàng phát triển và 
triển khai ứng dụng Web (Visual studio tích hợp: thiết kế, 
lập trình, debug test, deploy)
8
GV biên soạn: Trần Kim Hương

---

## Trang 8

Bài giảng Lập trình web aspx
Giới thiệu website được tạo với ASP.NET
❖Website trường ĐH Đồng Tháp
❖Website Khoa SP Toán – Tin
❖Website trung tậm ngoại ngữ - Tin học
❖……..
9
GV biên soạn: Trần Kim Hương

---

## Trang 9

Bài giảng Lập trình web aspx
Biên dịch vs Thông dịch
10
GV biên soạn: Trần Kim Hương
JS: thông dịch là trình duyệt web
PHP: web server
C#: biên dịch là Visual Studio

---

## Trang 10

Bài giảng Lập trình web aspx
3. Giới thiệu về .NET Framework
❖.NET Framework là nền tảng cho Microsoft .NET 
Platform
❖.NET Framework là môi trường cho việc xây dựng, triển 
khai và vận hành các ứng dụng Win/ Web
11
GV biên soạn: Trần Kim Hương

---

## Trang 11

Bài giảng Lập trình web aspx
Kiến trúc .NET Framework 2.0
12
GV biên soạn: Trần Kim Hương
➢Giúp đơn giản hóa quá 
trình phát triển, tích hợp 
sản phẩm
➢.NET Framework không 
phụ thuộc vào ngôn 
ngữ
➢Các ngôn ngữ đang 
được hỗ trợ: C++, C#, 
VB.NET, JScript

---

## Trang 12

Bài giảng Lập trình web aspx
Các version .NET Framework
13
GV biên soạn: Trần Kim Hương

---

## Trang 13

Bài giảng Lập trình web aspx
Kiến trúc .NET Framework
14
GV biên soạn: Trần Kim Hương
Cross-platform for .NET libraries

---

## Trang 14

Bài giảng Lập trình web aspx
Kiến trúc .NET Framework
15
GV biên soạn: Trần Kim Hương
Difference between .NET Framework 4.6, .Net Native and .Net Core

---

## Trang 15

Bài giảng Lập trình web aspx
❖Phần mềm cần thiết cho Developer/ Server/ 
Web Client?
17
GV biên soạn: Trần Kim Hương
Developer
Server (Host)
Web Client
- VS .Net 2029/ 
2022
- VS Code
- Browser (Chrome, 
…)
- Photoshop
- .Net Framework 
4.7
- MS SQL Server
- HĐH Window
- Browser 
(Chrome,…)

---

## Trang 16

Bài giảng Lập trình web aspx
4. Mô hình phát triển ứng dụng Web ASP.NET
18
GV biên soạn: Trần Kim Hương
Web Pages
Web Forms
MVC
- Đơn giản
- Mô hình giống 
PHP
- Cú pháp Razor
- .Lập trình hướng 
sự kiện
- Mô hình giống 
WinForms
- Nhiều Controls xây 
dựng sẵn
- Mẫu thiết kế 
Model-View-
Controller
- Linh hoạt, tách 
biệt thành phần 
nghiệp vụ, giao 
diện và xử lý

---

## Trang 17

Bài giảng Lập trình web aspx
Các thành phần của ud ASP.NET
19
GV biên soạn: Trần Kim Hương

---

## Trang 18

Bài giảng Lập trình web aspx
Các thành phần của ud ASP.NET
20
GV biên soạn: Trần Kim Hương

---

## Trang 19

Bài giảng Lập trình web aspx
5. Cơ chế xử lý 1 trang ASP.NET
21
GV biên soạn: Trần Kim Hương

---

## Trang 20

Bài giảng Lập trình web aspx
Tổng quan về lập trình ứng dụng web
❖Các mô hình tổ chức ứng dụng
▪Mô hình 1
▪Mô hình 2
24
GV biên soạn: Trần Kim Hương

---

## Trang 21

Bài giảng Lập trình web aspx
Tổng quan về lập trình ứng dụng web
❖Các mô hình tổ chức ứng dụng
▪Mô hình 3
25
GV biên soạn: Trần Kim Hương

---

## Trang 22

Bài giảng Lập trình web aspx
Tổng quan về lập trình ứng dụng web
❖Các mô hình tổ chức ứng dụng
▪Quá trình Request - Response
26
GV biên soạn: Trần Kim Hương

---

## Trang 23

Bài giảng Lập trình web aspx
Tổng quan về lập trình ứng dụng web
❖Quá trình xử lý tập tin ASP.NET
27
GV biên soạn: Trần Kim Hương

---

## Trang 24

Bài giảng Lập trình web aspx
Tổng quan về lập trình ứng dụng web
❖Quá trình xử lý tập tin ASP.NET
28
GV biên soạn: Trần Kim Hương

---

## Trang 25

Bài giảng Lập trình web aspx
6. Giới thiệu ASP.NET Web Form
❖Giới thiệu tính năng Asp.Net Web Form
❖Tạo Project Asp.Net Web Forms
▪Khởi động MS Visual Studio .Net
▪Giới thiệu các thư mục lưu trữ các đối tượng
▪Tạo 1 web form
▪Đối tượng Page
❖Biên dịch và Triển khai ứng dụng ASP.NET Web 
Forms
❖Cấu trúc 1 Web Form
29
GV biên soạn: Trần Kim Hương

---

## Trang 26

Bài giảng Lập trình web aspx
Giới thiệu tính năng Asp.Net Web Forms
❖Một mô hình phát triển ứng dụng web của ASP.NET
❖Lập trình hướng sự kiện (Even-driven Programming)
❖Tương tự mô hình lập trình ứng dụng Windows
▪Web Page được gọi là Web Form
❖Giúp xây dựng ứng dụng wev nhanh chóng, dễ dàng
30
GV biên soạn: Trần Kim Hương

---

## Trang 27

Bài giảng Lập trình web aspx
Giới thiệu tính năng Asp.Net Web Forms
31
GV biên soạn: Trần Kim Hương
ASP.NET Controls 
Categories
Key Features
Application Services 
APIs
Security
Maser Pages
Membership/ Role 
Manager
Data
Themes/ Skins
Personalization
Navigation
Localization
Site Navigation
Web Parts
Adaptive UI
Catching
Management

---

## Trang 28

Bài giảng Lập trình web aspx
C1. Tạo Project ASP.NET Web Form
❖Create a new project → ASP.NET Web Application 
(.NET Framework)→…→ Web Forms
32
GV biên soạn: Trần Kim Hương

---

## Trang 29

Bài giảng Lập trình web aspx
Tạo Web Form
❖R-click project → Add → New Item → Web (Web Forms) 
→ Web Form
33
GV biên soạn: Trần Kim Hương

---

## Trang 30

Bài giảng Lập trình web aspx
Tạo Web Form
❖Viết câu chào hiển thị lên website
34
GV biên soạn: Trần Kim Hương

---

## Trang 31

Bài giảng Lập trình web aspx
C2. Tạo Project Asp.Net Web Forms (Empty)
❖Khởi động MS Visual Studio .Net
▪VS 2019 → ASP.NET Web Application (.Net 
Framework) → Empty (check Web Form)
36
GV biên soạn: Trần Kim Hương

---

## Trang 32

Bài giảng Lập trình web aspx
C2. Tạo Project Asp.Net Web Forms (Empty)
❖Giới thiệu các thư mục lưu trữ các đối tượng
▪Tạo các folder: R-click project → Add ASP.NET folder 
→…
• App_Data: lưu trữ tập tin dữ liệu như .mdb, mdf, xml,…
• App_Code: lưu trữ các tập tin chứa source code, có 
phần mở rộng ..vb, .cs
• App_Themes: lưu trữ các tập tin dùng để tạo giao diện 
chung theo chủ đề, thường có phần mở rộng .skin, .css 
hoặc các file hình ảnh
37
GV biên soạn: Trần Kim Hương

---

## Trang 33

Bài giảng Lập trình web aspx
C2. Tạo Project Asp.Net Web Forms (Empty)
❖Giới thiệu các thư mục lưu trữ các đối tượng
38
GV biên soạn: Trần Kim Hương

---

## Trang 34

Bài giảng Lập trình web aspx
Tạo Project Asp.Net Web Forms
❖Tạo một Web Form
▪R-click project → Add New Item → Web Form (Web)
▪Có phần mở rộng .aspx (file giao diện) và aspx.cs (file 
code-behind)
▪Xác định trang khởi động: R-click trang được chọn → 
chọn Set As Start Page
▪Thi hành ứng dụng: F5
39
GV biên soạn: Trần Kim Hương

---

## Trang 35

Bài giảng Lập trình web aspx
Tạo Project Asp.Net Web Forms
❖Đối tượng Page
40
GV biên soạn: Trần Kim Hương

---

## Trang 36

Bài giảng Lập trình web aspx
Tạo Project Asp.Net Web Forms
❖Đối tượng Page
▪Thuộc tính
• IsPostBack: trả về trạng thái PostBack của trang
– False: là lần load đầu tiên của trang
– True: là lần load lại do submit bởi 1 control trong Web 
Form
• MaintainScrollPositionOnPostBack
– True: giữ nguyên vị trí mà người dùng đang đọc sau khi 
PostBack
– False: trở về vị trí đầu trang sau khi PostBack
41
GV biên soạn: Trần Kim Hương

---

## Trang 37

Bài giảng Lập trình web aspx
Cấu trúc của 1 Web Form
❖Một Web Form gồm các thành phần
▪Directives: chỉ định trang
▪Literal Text & HTML Tags
▪Code Declaration Blocks
▪Code Render Blocks
▪Web Controls
▪Server-side comments
44
GV biên soạn: Trần Kim Hương

---

## Trang 38

Bài giảng Lập trình web aspx
Cấu trúc Web Form – Code behind
❖Code behind là file mã nguồn (C#, VB.NET) chứa khai 
báo lớp có nhiệm vụ xử lý các logic nghiệp vụ của 
chương trình hay các sự kiện xảy ra khi người dùng 
tương tác với WebForm
❖Tên của lớp này trùng với tên của WebForm
▪Vd: nếu tên WebForm là Index → tên class là Index.cs
❖Tất cả các class xử lý sự kiện trên WebForm đều kế thừa từ 
lớp System.Web.UI.Page
❖Tất cả các class đều chứa hàm Page_Load tự động gọi thực hiện 
khi WebForm nhận request từ client
❖Hàm Page_Load dùng khởi tạo nội dung các control trên WebForm
46
GV biên soạn: Trần Kim Hương

---

## Trang 39

Bài giảng Lập trình web aspx
Directives
❖Chứa các chỉ thị cho biết cách thức Web Form được 
biên dịch
❖Được khai báo trong <%...%> và có thể đặt tại bất kỳ vị 
trí nào trên Web Form
❖Một 
số 
thuộc 
tính 
quan 
trọng: 
Language, 
AutoEventWireup, CodeFile,…
❖Ví dụ
48
GV biên soạn: Trần Kim Hương
<%@ Page Language="C#" AutoEventWireup="true“ 
CodeBehind="Index.aspx.cs" Inherits="Hello.Index" %>

---

## Trang 40

Bài giảng Lập trình web aspx
Web Controls (Chương 3)
❖Bao gồm 4 loại:
▪Html Server Control
▪ASP.NET Server Control
▪Validation Control
▪Web User Control
❖Được khai báo trong thẻ form
<form id="form1" runat="server"> ….. </form>
Ví dụ:
<asp:Label 
ID="Label1" 
runat="server" 
Text="Nhập 
Họ 
Tên:"></asp:Label>
<asp:TextBox ID="TextBox1" runat="server"></asp:TextBox>
50
GV biên soạn: Trần Kim Hương

---

## Trang 41

Bài giảng Lập trình web aspx
Server-side comments
❖Thể hiện các ghi chú trên Web Form
❖Sử dụng 1 trong 2 dạng:
▪Html Comment: <!—comment-- >
▪ASP.NET Comment: <%--comment--%>
❖Html comment sẽ được gửi về trình duyệt do đó không 
thích hợp để comment nội dung Asp.Net server-side 
code
❖ASP.NET comment dùng để ẩn thông tin với trình duyệt 
nhưng được xử lý bởi Asp.Net runtime
51
GV biên soạn: Trần Kim Hương

---

## Trang 42

Bài giảng Lập trình web aspx
Tổng kết
❖Các tính năng của ứng dụng ASP.NET Web Forms
❖Biên dịch và triển khai ứng dụng ASP.NET Web Forms
❖Cấu trúc Web Form
▪HTML tags & Literal Text
▪Page Directive <%@...%>
▪Code In-file vs Code Behind (Code Seperation)
▪Server-side Comment
52
GV biên soạn: Trần Kim Hương

---

## Trang 43

tkhuong@dthu.edu.vn
DISCUSSION!

---

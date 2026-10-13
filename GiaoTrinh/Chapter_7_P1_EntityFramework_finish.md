# Chapter_7_P1_EntityFramework_finish

> **Nguồn tài liệu**: Chapter_7_P1_EntityFramework_finish.pdf
> **Tổng số trang**: 56

## Mục lục nhanh

- [Trang 1: Biên soạn: ThS. TRẦN KIM HƢƠNG](#trang-1)
- [Trang 2: Web Technology with ASP.NET MVC](#trang-2)
- [Trang 3: Web Technology with ASP.NET MVC](#trang-3)
- [Trang 4: Web Technology with ASP.NET MVC](#trang-4)
- [Trang 5: Web Technology with ASP.NET MVC](#trang-5)
- [Trang 6: Web Technology with ASP.NET MVC](#trang-6)
- [Trang 7: Web Technology with ASP.NET MVC](#trang-7)
- [Trang 8: Web Technology with ASP.NET MVC](#trang-8)
- [Trang 9: Web Technology with ASP.NET MVC](#trang-9)
- [Trang 10: Web Technology with ASP.NET MVC](#trang-10)
- [Trang 11: Web Technology with ASP.NET MVC](#trang-11)
- [Trang 12: Web Technology with ASP.NET MVC](#trang-12)
- [Trang 13: Web Technology with ASP.NET MVC](#trang-13)
- [Trang 14: Web Technology with ASP.NET MVC](#trang-14)
- [Trang 15: Web Technology with ASP.NET MVC](#trang-15)
- [Trang 16: Web Technology with ASP.NET MVC](#trang-16)
- [Trang 17: Web Technology with ASP.NET MVC](#trang-17)
- [Trang 18: Web Technology with ASP.NET MVC](#trang-18)
- [Trang 19: Web Technology with ASP.NET MVC](#trang-19)
- [Trang 20: Web Technology with ASP.NET MVC](#trang-20)
- [Trang 21: Web Technology with ASP.NET MVC](#trang-21)
- [Trang 22: Web Technology with ASP.NET MVC](#trang-22)
- [Trang 23: Web Technology with ASP.NET MVC](#trang-23)
- [Trang 24: Web Technology with ASP.NET MVC](#trang-24)
- [Trang 25: Web Technology with ASP.NET MVC](#trang-25)
- [Trang 26: Web Technology with ASP.NET MVC](#trang-26)
- [Trang 27: Web Technology with ASP.NET MVC](#trang-27)
- [Trang 28: Web Technology with ASP.NET MVC](#trang-28)
- [Trang 29: Web Technology with ASP.NET MVC](#trang-29)
- [Trang 30: Web Technology with ASP.NET MVC](#trang-30)
- [Trang 31: Web Technology with ASP.NET MVC](#trang-31)
- [Trang 32: Web Technology with ASP.NET MVC](#trang-32)
- [Trang 33: Web Technology with ASP.NET MVC](#trang-33)
- [Trang 34: Web Technology with ASP.NET MVC](#trang-34)
- [Trang 35: Web Technology with ASP.NET MVC](#trang-35)
- [Trang 36: Web Technology with ASP.NET MVC](#trang-36)
- [Trang 37: Web Technology with ASP.NET MVC](#trang-37)
- [Trang 38: Web Technology with ASP.NET MVC](#trang-38)
- [Trang 39: Web Technology with ASP.NET MVC](#trang-39)
- [Trang 40: Web Technology with ASP.NET MVC](#trang-40)
- [Trang 41: Web Technology with ASP.NET MVC](#trang-41)
- [Trang 42: Web Technology with ASP.NET MVC](#trang-42)
- [Trang 43: Web Technology with ASP.NET MVC](#trang-43)
- [Trang 44: Web Technology with ASP.NET MVC](#trang-44)
- [Trang 45: Web Technology with ASP.NET MVC](#trang-45)
- [Trang 46: Web Technology with ASP.NET MVC](#trang-46)
- [Trang 47: Web Technology with ASP.NET MVC](#trang-47)
- [Trang 48: Web Technology with ASP.NET MVC](#trang-48)
- [Trang 49: Web Technology with ASP.NET MVC](#trang-49)
- [Trang 50: Web Technology with ASP.NET MVC](#trang-50)
- [Trang 51: Web Technology with ASP.NET MVC](#trang-51)
- [Trang 52: Web Technology with ASP.NET MVC](#trang-52)
- [Trang 53: Web Technology with ASP.NET MVC](#trang-53)
- [Trang 54: Web Technology with ASP.NET MVC](#trang-54)
- [Trang 55: Web Technology with ASP.NET MVC](#trang-55)
- [Trang 56: tkhuong@dthu.edu.vn](#trang-56)

---

## Trang 1

Biên soạn: ThS. TRẦN KIM HƢƠNG  
Email: tkhuong@dthu.edu.vn 
Chương
Chƣơng 
 7.
7. 
 
Entity Framework 
Entity Framework -
- 
 LINQ
LINQ 
 
(SQL Server)
(SQL Server)

---

## Trang 2

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Set up Page Default 
Trong file Web.config --> tag <configuration> bổ sung thêm 
đoạn code sau: 
 
3 
GV biên soạn: Trần Kim Hương 
<system.webServer> 
    <defaultDocument> 
      <files> 
        <add value="Home.aspx" /> 
      </files> 
    </defaultDocument> 
  </system.webServer>

---

## Trang 3

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Outline 
Entity Framework là gì? 
Kiến trúc EF 
Cài đặt EF 
Mô hình lập trình EF 
Database First 
Code First 
4 
tkhuong@dthu.edu.vn

---

## Trang 4

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
1. Entity Framework là gì? 
ADO.NET Entity Framework là một nền tảng được sử dụng 
để làm việc với database thông qua cơ chế ánh xạ Object 
Relational Mapping (ORM).  
EF chuyển các đối tượng CSDL (tables) thành các đối tượng 
.Net để sử dụng chúng trong truy vấn. 
 Có thể truy vấn, thao tác với database gián tiếp thông qua 
các đối tượng lập trình  làm việc dễ dàng với csdl mà không 
phải viết quá nhiều code 
 
5 
tkhuong@dthu.edu.vn

---

## Trang 5

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc Entity framework 
 
6 
tkhuong@dthu.edu.vn

---

## Trang 6

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc EF – Mô tả 
Application 
Là tầng chứa giao diện trang Web (HTML, CSS, 
Javascript, hình ảnh, …) và các đoạn mã nguồn (C#, VB) 
để tương tác dữ liệu với các tầng khác trong mô hình 
thông qua Object Services. 
Object Services 
Là tầng chứa quá trình tương tác giữa ứng dụng và 
database, để truy cập dữ liệu từ database và trả kết quả 
về giao diện.  
 
7 
tkhuong@dthu.edu.vn 
Bảng ánh xạ tương đương sau giữa các đối tượng trong database và EF

---

## Trang 7

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc EF – Mô tả 
Object Services (tt) 
Tự động sinh ra các class tương ứng với mô hình dữ liệu: 
ObjectContext đại diện cho một database; quản lý các kết nối, định 
nghĩa mô hình dữ liệu với metadata và thao tác với database. Lớp 
này cũng có thể thêm vào các phương thức đại diện cho các stored 
procedure trong database. 
ObjectSet<TEntity> là một  một tập hợp các entity. Mỗi đối tượng 
này tương ứng với một table. Có thể lấy được các đối tượng này 
thông qua các property tương ứng của ObjectContext. 
EntityObject, ComplexObject là các lớp tương ứng cho một dòng dữ 
liệu của table trong database. Khác biệt chính giữa hai loại này là 
ComplexObject không chứa primary key. 
EntityCollection<TEntity> và EntityReference<TEntity>: là các đối 
tượng thể hiện mối quan hệ (relationship) giữa hai entity class. Mỗi 
đối tượng này có thể được truy xuất thông qua các property của 
entity class. 
8 
tkhuong@dthu.edu.vn

---

## Trang 8

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc EF – Mô tả 
EntityClient Data Provider 
EntityClient là một data provider mới của ADO.NET dùng 
để truy xuất đến database. Được xây dựng bên trên các 
ADO.NET data provider cơ bản, EntityClient không truy 
xuất trực tiếp dữ liệu mà thông qua các data provider khác 
dựa vào các thông tin dữ liệu từ Entity Data Model. 
Một điểm khác biệt với các data provider khác là 
EntityClient sử dụng Entity SQL để truy vấn dữ liệu. Các 
lệnh Entity SQL sẽ được chuyển thành một cấu trúc lệnh 
dạng cây (command tree) và chuyển xuống cho các data 
provider khác. 
9 
tkhuong@dthu.edu.vn

---

## Trang 9

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc EF – Mô tả 
ADO.NET Data Providers 
Là tầng thấp nhất để dịch các truy vấn L2E (LINQ to 
Entity) thông qua cây lệnh thành các câu lệnh SQL và 
thực thi các câu lệnh trong hệ thống DBMS (database 
management system – hệ quản lý dữ liệu) nào đó.  
Tầng này kết với database sử dụng ADO.NET. 
10 
tkhuong@dthu.edu.vn

---

## Trang 10

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc EF – Mô tả 
EDM (Entity Data Model) 
Là mô hình dữ liệu được mô tả thông qua các ngôn ngữ theo 
chuẩn XML.  
EDM được chia làm 3 lớp là: Conceptual, Mapping và 
Logical. Mỗi lớp này được định nghĩa bởi ngôn ngữ riêng 
theo định dạng XML 
• Conceptual – Conceptual Schema Definition Language 
(CSDL): là ngôn ngữ định nghĩa các entity, relationship, hàm 
trong tập tin với phần mở rộng .csdl. Có thể tạo được các 
entity class (object layer). 
• Mapping – Mapping specification language (MSL): định nghĩa 
các ánh xạ giữa lớp conceptual và logical, nội dung này 
được lưu trong tập tin .msl. 
• Logical – Store Schema Definition Language (SSDL): định 
nghĩa mô hình lưu trữ của dữ liệu, lưu trữ trong tập tin .ssdl. 
11 
tkhuong@dthu.edu.vn

---

## Trang 11

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc EF – Mô tả 
EDM (Entity Data Model) 
12 
tkhuong@dthu.edu.vn

---

## Trang 12

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
2. Kiến trúc Entity framework 
Vị trí của EF trong mô hình lập trình và phát triển Web 
13 
tkhuong@dthu.edu.vn

---

## Trang 13

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
3. Cài đặt Entity Framework 
Cách 1. Sử dụng Manage NuGet Packages 
Phiên bản mới nhất của EF có sẵn tại gói EntityFramework tại 
Nuget (http://nuget.org/packages/EntityFramework/). 
R-click thư mục References (hoặc bin) trong dự án Web và chọn 
Manage NuGet Packages.  tìm và cài đặt gói Entity 
Framework vào dự án Web. 
Cách 2. Sử dụng Package manager console 
Menu Tools  NuGet Package Manager  Package Manager 
Console 
cửa sổ Package Manager Console  nhập cụm từ Install-
Package EntityFramework để tiến hành cài đặt Entity 
Framework cho project. 
14 
tkhuong@dthu.edu.vn

---

## Trang 14

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
4. Mô hình lập trình EF 
 
 
17 
tkhuong@dthu.edu.vn 
•
Existing Database  Generated Data Model (.edmx)  code 
•
Data Model (.edmx)  code  Generated Database 
•
Data Model (class)  Generated Database

---

## Trang 15

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
 
18 
tkhuong@dthu.edu.vn

---

## Trang 16

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Database First 
Existing Database  Generated Data Model (.edmx) 
Thiết kế database trước, sau đó dùng VS tạo lớp entity, 
DataContext để làm việc với CSDL 
Cách thực hiện: 
Tạo database trong SQL Server 
Tạo Entity Data Model (kết nối database) 
Xây dựng Entity framework API 
R-click thư mục Model  Add New Item  Data  ADO.NET Enity 
Data Model  name (QLBS_Model)  EF Designer from 
Database Microsoft SQL Server --> .\sqlexpress 
19 
tkhuong@dthu.edu.vn

---

## Trang 17

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Database First 
20 
tkhuong@dthu.edu.vn 
Database Context 
Entity

---

## Trang 18

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Database First 
21 
tkhuong@dthu.edu.vn 
Database Context

---

## Trang 19

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Database First 
Chi tiết Entity 
Tên thực thể  Tên bảng 
Tên thuộc tính  Tên cột 
Thực thể kết hợp 1-N 
22 
tkhuong@dthu.edu.vn

---

## Trang 20

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Database First 
24 
tkhuong@dthu.edu.vn 
Thay đổi Database trong SQL Server (thêm bảng, thay 
đổi thuộc tính,…) 
 Cập nhật lại Entity Data Model 
R-click entity Model  Update Model from Database  
Refesh  Finish

---

## Trang 21

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Demo  
Thực hành DB First và LINQ to EntityFramework 
Sử dụng DB QLNV(3 table NhanVien, ChucVu, 
BoPhan) 
Làm việc với các control ListBox, DropdownList, 
CheckBox GridView 
 
 
26 
tkhuong@dthu.edu.vn 
* Liên kết các page 
<a class="nav-link" href="TestLayoutTest.aspx">QL Nhân Viên</a> 
 
<asp:HyperLink ID="HyperLink1" 
NavigateUrl="~/TestLayoutBoostrap.aspx" runat="server"> 
 
HyperLink 
</asp:HyperLink>

---

## Trang 22

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
CSDL QLNV 
27 
tkhuong@dthu.edu.vn

---

## Trang 23

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Demo ListBox, DropDownList 
Tạo 1 web form: thiết kế gồm ListBox, DropDownList (đặt ID) 
và 1 button, 1 label 
Add reference Entity Framework 
Tạo folder Model chứa ADO.Net Entity Data Model 
R-click folder  Add New Item  ADO.Net Entity Data Model (Data) 
Viết sự kiện Page_Load: lấy ra danh sách bộ phận cho 
ListBox 
ModelNV _context = new ModelNV(); 
lstBoPhan.DataSource = _context.Bophans.ToList(); 
lstBoPhan.DataValueField = "MaBP"; 
lstBoPhan.DataTextField = "TenBP"; 
lstBoPhan.DataBind(); 
 
28 
tkhuong@dthu.edu.vn

---

## Trang 24

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Demo ListBox, DropDownList 
Chú ý: mỗi khi load page (nhấn btn send) sẽ load lại danh sách Bộ 
phận  không hiển thị được giá trị được chọn 
 khắc phục: kiểm tra thêm sự kiện khi load page Page.IsPostBack 
load lần đầu tiên mới load danh sách bộ phận 
 
29 
tkhuong@dthu.edu.vn 
 if (!Page.IsPostBack){....}

---

## Trang 25

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView 
Hiển thị danh sách Chức vụ 
Tạo web form thả control GridView, property: ID 
Thuộc tính DataSource, DataBind 
30 
tkhuong@dthu.edu.vn 
private ModelNV _context = new ModelNV(); 
 
var cv = _context.ChucVus.ToList();                 
gvChucVu.DataSource = cv; 
gvChucVu.DataBind();

---

## Trang 26

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
BT - GridView 
Hãy hiển thị danh sách Nhân viên, sử dụng GridView 
31 
tkhuong@dthu.edu.vn

---

## Trang 27

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Ôn tập LINQ 
Các truy vấn trong LINQ To Entity 
 
32 
tkhuong@dthu.edu.vn

---

## Trang 28

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView - Paging 
Thiết lập thêm Property:  
AllowPaging: True 
PageSize: 10 
EnableSortingAndPagingCallback: True (false sẽ bị lỗi) 
Chú ý: mỗi lần chuyển sang trang kế phải load lại dữ liệu  không 
sử dụng if(!Page.isPostback) 
 
33 
tkhuong@dthu.edu.vn

---

## Trang 29

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – format column (1) 
Tạo 1 web form mới, kéo thả GridView (ID) 
Edit Column…  BoundField (trường lấy dữ liệu cơ bản nhất), 
Auto-generate fields: bỏ check, Header Text, DataField 
Auto Format…  chọn mẫu hiển thị 
 
 
34 
tkhuong@dthu.edu.vn

---

## Trang 30

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – format column (2) 
Viết câu query lấy ra 1 số column cần hiển thị tương ứng với trong 
field thiết lập 
 
 
35 
tkhuong@dthu.edu.vn

---

## Trang 31

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – Select command (1) 
Tạo web form, thả GridView, Auto Format, Edit Column; label result 
Add Select (CommandField): Button Type: Button; Select Text: Chọn 
Add BoundField: Header Text, DataField 
Tắt Auto-generate fields 
 
 
36 
tkhuong@dthu.edu.vn

---

## Trang 32

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – Select command (2) 
Click vào button Chọn sẽ hiển thị kết quả chọn vào label result 
Sự kiện SelectedIndexChange;  
 
 
 
gvChucVu.SelectedRow.Cells[1].Text 
 
 
37 
tkhuong@dthu.edu.vn

---

## Trang 33

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – Parent, Child 
Tạo web form lấy ra danh sách Bộ phận, chọn bộ phận nào thì sẽ hiện 
thị danh sách Nhân viên thuộc bộ phận đó 
Sử dụng GridView BoPhan, GridView NhanVien (property visible: False) 
 
 
 
 
 
 
 
38 
tkhuong@dthu.edu.vn

---

## Trang 34

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – DropDownList 
Tạo web form với DropDownList lấy ra danh sách Bộ phận, chọn bộ 
phận nào thì sẽ hiện thị danh sách Nhân viên thuộc bộ phận đó 
Sử dụng DropDownList BoPhan (ID, AutoPostback=false), GridView 
NhanVien (ID, property visible: False), Button Hiển thị danh sách (ID, 
Text) 
 
 
 
 
 
 
 
39 
tkhuong@dthu.edu.vn

---

## Trang 35

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – CheckBox (1) 
Tạo web form với GridView (ID, Edit Column: BoundField, 
TemplateField: gắn control CheckBox) 
TemplateField: Edit Tempate  ItemTemplate: kéo control CheckBox 
vào  EndEditTemplate 
Button Result, Label Result: show ra ID của row đc check 
 
 
 
 
 
 
 
40 
tkhuong@dthu.edu.vn 
GridViewRow row in gvNhanVien.Rows 
CheckBox chk = (CheckBox)row.FindControl("chkNhanVien");

---

## Trang 36

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – CheckBox (2) 
Design UI như mẫu (sử dụng Table để chia vùng) 
 
 
 
 
 
 
 
41 
tkhuong@dthu.edu.vn

---

## Trang 37

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Repeater 

Note: Repeater không hỗ trợ paging, page chỉ hỗ trợ GridView và ListView 
42 
tkhuong@dthu.edu.vn 
Sử dụng control Repeater kết hợp 
ItemTemplate 
Thuộc 
tính 
DataSource 
của 
Repeater 
Hiển thị dữ liệu:  
<%# Eval("HoTen") %> 
<asp:Repeater ID="RepeaterNV" runat="server"> 
  
<ItemTemplate>  
 
 
<%# Eval("HoTen") %> 
 
</ItemTemplate> 
</asp:Repeater>

---

## Trang 38

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
ListView  
43 
tkhuong@dthu.edu.vn 
Sử dụng control ListView kết hợp 
ItemTemplate 
Paging: sử dụng control DataPager 
kết 
hợp 
Fields 
và 
control 
NextPreviousPagerField 
Thuộc tính DataSource của ListView 
Hiển thị dữ liệu:  
<%# Eval("HoTen") %> 
<asp:ListView ID="RepeaterNV" runat="server"> 
 
<ItemTemplate>  
 
 
<%# Eval("HoTen") %> 
 
</ItemTemplate> 
</asp:ListView>

---

## Trang 39

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
ListView - DataPager 
44 
tkhuong@dthu.edu.vn 
<asp:DataPager ID="DataPagerNV" runat="server" 
PagedControlID="RepeaterNV" OnPreRender="DataPagerNV_PreRender" 
PageSize="5"> 
 
<Fields> 
 
 
 <asp:NumericPagerField ButtonType="Link" /> 
 
 
<asp:NextPreviousPagerField ButtonType="Button" 
ShowFirstPageButton="true" ShowLastPageButton="true" /> 
 
</Fields> 
</asp:DataPager> 
Paging: sử dụng control DataPager kết hợp Fields và 
control NextPreviousPagerField 
Thuộc tính PagedControlID : chỉ định control phân 
trang 
Sự kiện: OnPreRender 
Control NextPreviousPagerField: hiển thị dạng button 
Next/Previous 
Hoặc control NumericPagerField: hiển thị dạng số 
trang

---

## Trang 40

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – Form Thêm mới (1) 
Design UI như mẫu (sử dụng Table để chia vùng) gồm: GridView, 
button, Panel, TextBox 
Load trang sẽ ẩn Panel, nhấn Create New thì show ra; Cancel thì clear 
text và ẩn Panel; Insert thì add data vào DB 
 
 
 
 
 
 
45 
tkhuong@dthu.edu.vn

---

## Trang 41

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
GridView – Form Thêm mới (2) 
Kiểm tra TextBox trước khi thêm 
Khi thêm mới xong thì load lại Data 
 
 
 
 
 
 
46 
tkhuong@dthu.edu.vn

---

## Trang 42

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
BT - Cải tiến: Chuyển đổi giữa các trang 
Cải tiến Form thêm mới bài trƣớc 
Tạo form thêm mới ở 1 trang khác, khi nhấn Thêm sẽ 
chuyển sang trang mới 
Khi thêm mới thành công or Cancel thì trở về trang 
danh sách 
Thực hiện Thêm mới cho Nhân Viên có Ngày Sinh: 
DateTime 
 
47 
tkhuong@dthu.edu.vn 
Server.Transfer("~/Form/BoPhanForm.aspx");

---

## Trang 43

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
BT – Control Calendar (Thêm Nhân Viên) 
Thêm Nhân Viên Mới 
Thực hiện Thêm mới cho Nhân 
Viên có Ngày Sinh: DateTime 
Sự kiện: 
Calendar1_SelectionChanged 
Khi chọn ngày sẽ gán vào 
TextBox và ẩn Calendar 
48 
tkhuong@dthu.edu.vn 
Calendar1.SelectedDate.ToString("dd/MM/yyyy");

---

## Trang 44

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Quản trị Website (Tự học) 
Ncuu về Phân quyền ngƣời dùng, Login,… 
49 
tkhuong@dthu.edu.vn

---

## Trang 45

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình lập trình EF 
 
 
50 
tkhuong@dthu.edu.vn

---

## Trang 46

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Code First 
Data Model (class)  Generated Database 
Tạo các class ứng dụng và class entity 
Khi ứng dụng được run sẽ tạo ra 1 database tương ứng 
với các class trong SQL Server 
51 
tkhuong@dthu.edu.vn

---

## Trang 47

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Mô hình EF – Code First 
Demo tạo database bằng Code First 
Employee (EmployeeId, FullName, Birthday, Email) 
Project (ProjectId, ProjectName, StartDate, FinishDate) 
ProjectJoin 
(ProjectJoinId, 
EmployeeId, 
ProjectId, 
StartDate, FinishDate) 
52 
tkhuong@dthu.edu.vn

---

## Trang 48

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Hƣớng dẫn 
B1. Cài đặt Entity Framework 
B2. Tạo các class biểu diễn dữ liệu tương ứng các entity 
B3. Tạo các thuộc tính navigation đến các entity 
B4. Tạo Class Data Context 
B5. Tạo controller with views, using EF 
53 
tkhuong@dthu.edu.vn

---

## Trang 49

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Hƣớng dẫn 
B2. Tạo các class biểu diễn dữ liệu tƣơng ứng các entity 
54 
tkhuong@dthu.edu.vn 
public class Employee 
    { 
        public string EmployeeId { get; set; } 
        public string FullName { get; set; } 
        public DateTime Birthday { get; set; } 
        public string Email { get; set; } 
    } 
public class Project 
    { 
        public string ProjectId { get; set; } 
        public string ProjectName { get; set; } 
        public DateTime StartDate { get; set; } 
        public DateTime FinishDate { get; set; 
} 
    } 
public class ProjectJoin 
    { 
        public string ProjectJoinId { get; set; } 
        public string EmployeeId { get; set; } 
        public string ProjectId { get; set; } 
        public DateTime StartDate { get; set; } 
        public DateTime FinishDate { get; set; 
} 
    }

---

## Trang 50

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Hƣớng dẫn 
B3. Tạo các thuộc tính navigation đến các entity 
55 
tkhuong@dthu.edu.vn 
public class Employee 
{ 
 
………… 
public ICollection<ProjectJoin> Employees { get; set; } 
} 
public class Project 
    { 
 
…… 
 
public ICollection<ProjectJoin> Projects { get; set; } 
    } 
public class ProjectJoin 
    { 
         public virtual Project Project { get; set; } 
        public virtual Employee Employee { get; set; } } 
    }

---

## Trang 51

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Hƣớng dẫn 
B4. Tạo các Data Context 
56 
tkhuong@dthu.edu.vn 
 public class ProjectManagement:DbContext 
    { 
        public DbSet<Employee> Employee { get; set; } 
        public DbSet<Project> Project { get; set; } 
        public DbSet<ProjectJoin> ProjectJoin { get; set; } 
    }

---

## Trang 52

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Hƣớng dẫn 
B5. Tạo controller with views, using EF 
Add Controller  Name (Project)  Model (chọn table 
Project)  Data Context class (ProjectManagement)  
Add 
 Run xem kết quả 
 Tự động sinh ra Database trong SQL Server 
57 
tkhuong@dthu.edu.vn

---

## Trang 53

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Code First 
Khai báo tường minh cho Database  Bổ sung các 
thuộc tính cho entity 
Đặt tên table 
using System.ComponentModel.DataAnnotations.Schema; 
[Table ("Employee")] //đặt ngoài class 
Khai báo thuộc tính khóa (mặc định thuộc tính nào có 
Id EF tự hiểu là key) 
using System.ComponentModel.DataAnnotations; 
[Key] 
Khai báo thuộc tính khóa ngoại 
[ForeignKey ("Employee")] 
58 
tkhuong@dthu.edu.vn

---

## Trang 54

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Code First 
Đặt tên cho Database  
Viết thêm phương thức cho class DbContext 
• Mở file ProjectManagement.cs và bs pthuc 
 
 
 
 
Chỉ rõ chuỗi kết nối đến Database cho EF 
59 
tkhuong@dthu.edu.vn 
public ProjectManagement() : base("name=ProjectManagement") 
        { 
        } 
 Run sẽ sinh ra csdl có tên theo name 
<add name="ProjectManagement"  
connectionString="Data Source=.\sqlexpress; 
Initial Catalog=ProjectManagement; 
Integrated Security=True"  
providerName="System.Data.SqlClient" />

---

## Trang 55

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Code First 
Thay đổi cấu trúc của Database  
Vd. Thêm thuộc tính Description vào table Project  lỗi 
Cấu hình cho sự thay đổi trong file Global.asax 
 
 
 
 
 
60 
tkhuong@dthu.edu.vn 
using System.Data.Entity; 
using Demo_CodeFirst.Models; 
 
Database.SetInitializer(new 
DropCreateDatabaseIfModelChanges<ProjectManagement>()); 
 
khi có thay đổi cầu trúc EF sẽ xóa và tạo lại database

---

## Trang 56

tkhuong@dthu.edu.vn

---

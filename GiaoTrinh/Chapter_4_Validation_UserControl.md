# Chapter_4_Validation_UserControl

> **Nguồn tài liệu**: Chapter_4_Validation_UserControl.pdf
> **Tổng số trang**: 44

## Mục lục nhanh

- [Trang 1: ThS. TRẦN KIM HƯƠNG – KHOA CÔNG NGHỆ SỐ VÀ KỸ THUẬT](#trang-1)
- [Trang 2: Bài giảng Lập trình Web Aspx](#trang-2)
- [Trang 3: Bài giảng Lập trình Web Aspx](#trang-3)
- [Trang 4: Bài giảng Lập trình Web Aspx](#trang-4)
- [Trang 5: Bài giảng Lập trình Web Aspx](#trang-5)
- [Trang 6: Bài giảng Lập trình Web Aspx](#trang-6)
- [Trang 7: Bài giảng Lập trình Web Aspx](#trang-7)
- [Trang 8: Bài giảng Lập trình Web Aspx](#trang-8)
- [Trang 9: Bài giảng Lập trình Web Aspx](#trang-9)
- [Trang 10: Bài giảng Lập trình Web Aspx](#trang-10)
- [Trang 11: Bài giảng Lập trình Web Aspx](#trang-11)
- [Trang 12: Bài giảng Lập trình Web Aspx](#trang-12)
- [Trang 13: Bài giảng Lập trình Web Aspx](#trang-13)
- [Trang 14: Bài giảng Lập trình Web Aspx](#trang-14)
- [Trang 15: Bài giảng Lập trình Web Aspx](#trang-15)
- [Trang 16: Bài giảng Lập trình Web Aspx](#trang-16)
- [Trang 17: Bài giảng Lập trình Web Aspx](#trang-17)
- [Trang 18: Bài giảng Lập trình Web Aspx](#trang-18)
- [Trang 19: Bài giảng Lập trình Web Aspx](#trang-19)
- [Trang 20: Bài giảng Lập trình Web Aspx](#trang-20)
- [Trang 21: Bài giảng Lập trình Web Aspx](#trang-21)
- [Trang 22: Bài giảng Lập trình Web Aspx](#trang-22)
- [Trang 23: Bài giảng Lập trình Web Aspx](#trang-23)
- [Trang 24: Bài giảng Lập trình Web Aspx](#trang-24)
- [Trang 25: Bài giảng Lập trình Web Aspx](#trang-25)
- [Trang 26: Bài giảng Lập trình Web Aspx](#trang-26)
- [Trang 27: Bài giảng Lập trình Web Aspx](#trang-27)
- [Trang 28: Bài giảng Lập trình Web Aspx](#trang-28)
- [Trang 29: Bài giảng Lập trình Web Aspx](#trang-29)
- [Trang 30: Bài giảng Lập trình Web Aspx](#trang-30)
- [Trang 31: Bài giảng Lập trình Web Aspx](#trang-31)
- [Trang 32: Bài giảng Lập trình Web Aspx](#trang-32)
- [Trang 33: Bài giảng Lập trình Web Aspx](#trang-33)
- [Trang 34: Bài giảng Lập trình Web Aspx](#trang-34)
- [Trang 35: Bài giảng Lập trình Web Aspx](#trang-35)
- [Trang 36: Bài giảng Lập trình Web Aspx](#trang-36)
- [Trang 37: Bài giảng Lập trình Web Aspx](#trang-37)
- [Trang 38: Bài giảng Lập trình Web Aspx](#trang-38)
- [Trang 39: Bài giảng Lập trình Web Aspx](#trang-39)
- [Trang 40: Bài giảng Lập trình Web Aspx](#trang-40)
- [Trang 41: Bài giảng Lập trình Web Aspx](#trang-41)
- [Trang 42: Bài giảng Lập trình Web Aspx](#trang-42)
- [Trang 43: Bài giảng Lập trình Web Aspx](#trang-43)
- [Trang 44: tkhuong@dthu.edu.vn](#trang-44)

---

## Trang 1

ThS. TRẦN KIM HƯƠNG – KHOA CÔNG NGHỆ SỐ VÀ KỸ THUẬT 
tkhuong@dthu.edu.vn 
Validation & User Controls 
Validation & User Controls trên
trên 
 
Web Forms
Web Forms

---

## Trang 2

Bài giảng Lập trình Web Aspx 
NỘI DUNG 
2 
tkhuong@dthu.edu.vn 
Validator Controls 
Web User Control

---

## Trang 3

Bài giảng Lập trình Web Aspx 
VALIDATOR CONTROLS 
Kiểm tra tính đúng đắn của dữ liệu do client nhập vào khi 
trang được gửi về server 
Hỗ trợ kiểm tra ở cả hai phía Client – Side và Server - Site 
3 
GV biên soạn: Trần Kim Hương

---

## Trang 4

Bài giảng Lập trình Web Aspx 
VALIDATOR CONTROLS 
Một số thuộc tính cơ bản 
ControlToValidate: tên điều khiển cần kiểm tra 
Text: nội dung thông báo xuất hiện khi có lỗi 
ErrorMessage: nội dung thông báo xuất hiện trong control 
ValidationSummary 
EnableClientScript: cho phép thực hiện kiểm tra phía Client hay 
không (True/ False) 
SetFocusError (True/ False): đặt con trỏ vào điều khiển khi dữ 
liệu không hợp lệ 
ValidationGroup: tên nhóm, nhóm các điều khiển có cùng giá trị 
ValidationGroup 
4 
GV biên soạn: Trần Kim Hương

---

## Trang 5

Bài giảng Lập trình Web Aspx 
Các loại Validation Control 
5 
GV biên soạn: Trần Kim Hương 
Validation control 
Sử dụng khi 
RequiredFieldValidator 
Kiểm tra nếu dữ liệu trong control khác giá trị cho 
trước (mặc định là rỗng) 
CompareValidator 
Kiểm tra nếu mục dữ liệu nhập trong control 
giống với control khác hoặc so sánh với 1 giá trị 
cụ thể 
RangeValidator 
Kiểm tra nếu mục dữ liệu nhập trong control nằm 
trong khoảng 2 giá trị 
RegularExpressionValidator 
Kiểm tra nếu mục dữ liệu nhập trong control thỏa 
1 công thức định dạng chỉ định 
CustomValidator 
Kiểm tra tính đúng đắn của dữ liệu nhập vào 
control sử dụng client-side script hoặc server-side 
code hoặc cả 2 
ValidationSummary 
Hiển thị tất cả lỗi kiểm tra xảy ra trong trang

---

## Trang 6

Bài giảng Lập trình Web Aspx 
Sử dụng Validation Control 
Các bước: 
Kéo thả 1 validation control vào Web Form 
Thiết lập các thuộc tính cho validation control: 
ControlToValidate là control muốn kiểm tra 
ErrorMessage: Thông báo lỗi 
Text: Hiển thị của validate control 
Sử dụng ValidationSummary control để hiển thị tất cả các lỗi 
xảy ra trong trang 
6 
GV biên soạn: Trần Kim Hương

---

## Trang 7

Bài giảng Lập trình Web Aspx 
Demo 
Thiết 
lập 
Validation 
cho 
txtTenDN 
Control  
RequireFieldValidator: Id, 
Text:*, 
ControlToValid: 
txtTenDN, ErrorMessage: 
không rỗng 
Control 
ValidationSummary: hiển 
thị ErrorMessage ra ui; 
ShowMessageBox: 
true 
(hiển thị dạng popup 
7 
GV biên soạn: Trần Kim Hương

---

## Trang 8

Bài giảng Lập trình Web Aspx 
Khắc phục Lỗi 
8 
GV biên soạn: Trần Kim Hương 
Vào file Web.config thêm đoạn code sau trong thẻ <configuration> 
<appSettings> 
<add key="ValidationSettings:UnobtrusivevalidationMode" 
value="None"/> 
</appSettings>

---

## Trang 9

Bài giảng Lập trình Web Aspx 
Required Field Validator 
Kiểm tra giá trị trong điều khiển phải được nhập 
Thuộc tính InitialValue: 
Giá trị khởi động 
Giá trị nhập vào phải khác giá trị của thuộc tính này 
9 
GV biên soạn: Trần Kim Hương

---

## Trang 10

Bài giảng Lập trình Web Aspx 
Required Field Validator 
Thuộc tính 
Ý nghĩa 
ControlToValidat
e 
Control dùng để thực hiện kiểm tra 
InitialValue 
Giá trị dùng để so sánh, mặc định 
là rỗng 
10 
GV biên soạn: Trần Kim Hương 
Mẫu số: <asp:TextBox ID="txtMauSo" 
runat="server"></asp:TextBox>        
 
<asp:RequiredFieldValidator 
ID="RequiredFieldValidator1" runat="server" 
ErrorMessage="RequiredFieldValidator" 
ControlToValidate="txtMauSo" 
InitialValue="0">Mẫu số phải khác 0 
</asp:RequiredFieldValidator>

---

## Trang 11

Bài giảng Lập trình Web Aspx 
Compare Validator 
So sánh gía trị của một điều khiển với giá trị của một điều 
khiển khác 
So sánh giá trị của một điều khiển với một giá trị được xác 
định trước 
Kiểm tra kiểu dữ liệu 
Trong trường hợp không nhập dữ liệu, điều khiển sẽ không 
thực hiện kiểm tra 
Thuộc tính 
ControlToComare (ưu tiên): điều khiển dùng để so sánh 
Operator: toán tử so sánh 
Type (String, Double, Date, Currency): kiểu dữ liệu 
ValueToCompare: giá trị dùng để so sánh 
11 
GV biên soạn: Trần Kim Hương

---

## Trang 12

Bài giảng Lập trình Web Aspx 
Compare Validator 
12 
GV biên soạn: Trần Kim Hương 
Thuộc tính 
Ý nghĩa 
ControlToValidate 
Control dùng để thực hiện kiểm tra 
ControlToCompare 
Control dùng để so sánh 
Operator 
Toán tử so sánh: Equal, GreaterThan, 
GreaterThanEqual, LessThan, LessThanEqual, 
NotEqual, hoặc DataTypeCheck 
ValueToCompare 
Giá trị hằng số để so sánh ControlToVaidate với 
Operator 
Type 
Kiểm tra kiểu dữ liệu của ControlToValidate: String, 
Integer, Double, Date, Currency

---

## Trang 13

Bài giảng Lập trình Web Aspx 
Ví dụ kiểm tra mật khẩu và xác nhận mk 
13 
GV biên soạn: Trần Kim Hương 
Tạo form gồm 2 textbox cho phép 
nhập password và confirm password, 
sử dụng control CompareValidator để 
kiểm tra như sau:

---

## Trang 14

Bài giảng Lập trình Web Aspx 
Ví dụ kiểm tra dữ liệu số >= 18 
14 
GV biên soạn: Trần Kim Hương 
Tạo form gồm 1 textbox cho phép 
nhập 
tuổi, 
sử 
dụng 
control 
CompareValidator để kiểm tra tuổi phải 
>=18 như sau:

---

## Trang 15

Bài giảng Lập trình Web Aspx 
Ví dụ kiểm tra dữ liệu kiểu ngày tháng 
15 
GV biên soạn: Trần Kim Hương 
Tạo form gồm 1 textbox cho phép 
nhập ngày tháng năm, sử dụng control 
CompareValidator để kiểm tra ngày nhập 
có phải kiểu date không

---

## Trang 16

Bài giảng Lập trình Web Aspx 
Range Validator 
Kiểm tra giá trị của điều khiển nằm trong đoạn [min-max] 
Thuộc tính 
MinimumValue: giá trị nhỏ nhất 
MaximumValue: giá trị lớn nhất 
Type: xác định kiểu dữ liệu để kiểm tra (String/ 
Integer/Double/Date/Currency) 
16 
GV biên soạn: Trần Kim Hương

---

## Trang 17

Bài giảng Lập trình Web Aspx 
17 
GV biên soạn: Trần Kim Hương 
Range Validator 
Thuộc tính 
Ý nghĩa 
ControlToValidate 
Control dùng để thực hiện kiểm tra 
MinimumValue 
Giá trị cận dưới 
MaximumValue 
Giá trị cận trên 
Type 
Kiểm tra kiểu dữ liệu của 
ControlToValidate: String, Integer, 
Double, Date, Currency

---

## Trang 18

Bài giảng Lập trình Web Aspx 
Regular Expression Validator 
Kiểm tra giá trị của điều khiển phải theo mẫu quy định 
Thuộc tính 
ValidationExpression: quy định mẫu kiểm tra dữ liệu dựa 
vào các ký hiệu quy định 
18 
GV biên soạn: Trần Kim Hương

---

## Trang 19

Bài giảng Lập trình Web Aspx 
19 
GV biên soạn: Trần Kim Hương 
Regular Expression Validator

---

## Trang 20

Bài giảng Lập trình Web Aspx 
20 
GV biên soạn: Trần Kim Hương 
Regular Expression Validator 
Ký hiệu 
Ý nghĩa 
^ … S 
Dấu hiệu bắt đầu và kết thúc một Expression 
\t 
Có chứa Ký tự Tab 
\n 
Có chứa ký tự xuống dòng 
. 
Có chứa ký tự bất kỳ khác \n 
[qwerty] 
Có chứa ký tự bất kỳ trong ngoặc vuông 
[^qwerty] 
Không chứa ký tự nào trong ngoặc vuông 
[a-z] 
Có chứa ký tự trong khoảng từ a đến z 
\w 
Có chứa một từ bất kỳ (word). Tương tự [a-zA-Z0-0] 
\W 
Có chứa một choỗi bất kỳ không phải là một từ (nonword) 
| 
Hoặc

---

## Trang 21

Bài giảng Lập trình Web Aspx 
21 
GV biên soạn: Trần Kim Hương 
Regular Expression Validator 
Ký hiệu 
Ý nghĩa 
\s 
Có chứa ký tự khoảng trắng 
\S 
Không chứa ký tự khoảng trắng 
\d 
Có chứa ký tự số 
\D 
Không chứa ký tự số 
* 
Chỉ định 0 hoặc nhiều 
+ 
Chỉ định 1 hoặc nhiều 
? 
Chỉ định 0 hoặc 1 
{n} 
Chỉ định có đúng chính xác n lần 
{n,} 
Chỉ định có nhiều hơn n lần 
{n,m} 
Chỉ định có từ n đến m lần

---

## Trang 22

Bài giảng Lập trình Web Aspx 
ValidationSummary 
Dùng để hiển thị danh sách các lỗi đang có trên trang web 
Nội dung thông báo lỗi lấy từ nội dung khai báo trong thuộc tính 
ErrorMessage 
Thuộc tính 
HeaderText: chuỗi văn bản của dòng tiêu đề 
ShowMessageBox (True/ False): thể hiện hộp thoại thông báo 
lỗi trên Browser? 
ShowSummary (True/ False): thể hiện danh sách thông báo lỗi 
tại vị trí của điiều khiển trên Browser? 
 
22 
GV biên soạn: Trần Kim Hương

---

## Trang 23

Bài giảng Lập trình Web Aspx 
23 
GV biên soạn: Trần Kim Hương 
Validation Summary Validator 
ShowMessageBox: True  show popup

---

## Trang 24

Bài giảng Lập trình Web Aspx 
CustomValidator 
Tự viết mã lệnh kiểm tra lỗi chạy trên server hoặc client 
Trên Client 
Chỉ 
định 
đoạn 
script 
kiểm 
tra 
cho 
thuộc 
tính 
ClientValidationFunction của CustomValidator 
ValidateEmptyText (True/ False): có kiểm tra khi giá trị 
nhập là rỗng? 
Trên Server 
Đặt mã lệnh kiểm tra trong hàm xử lý sự kiện 
ServerValidate 
24 
GV biên soạn: Trần Kim Hương

---

## Trang 25

Bài giảng Lập trình Web Aspx 
Ví dụ: Tự kiểm tra trên Client 
25 
GV biên soạn: Trần Kim Hương 
 <script language="javascript"> 
function ClientValidate(e, args) { 
 
debugger 
 
args.IsValid = false; 
       if (args.Value === "huong") 
           args.IsValid = true; 
                   } 
</script>

---

## Trang 26

Bài giảng Lập trình Web Aspx 
Ví dụ: Tự kiểm tra trên Server 
26 
GV biên soạn: Trần Kim Hương 
protected void 
CustomValidator1_ServerValidate(object 
source, ServerValidateEventArgs args) 
        { 
            args.IsValid = false; 
            if (txtCheck.Text == "abc") 
                args.IsValid = true; 
        }

---

## Trang 27

Bài giảng Lập trình Web Aspx 
Thiết lập Validation Group 
Thiết lập nhóm các control sẽ kiểm tra trong quá trình 
Validation 
27 
GV biên soạn: Trần Kim Hương 
<div> 
 
<asp:TextBox ID="txtValidateGroup" runat="server"></asp:TextBox> 
 
<asp:RequiredFieldValidator ID="RequiredFieldValidator2" 
runat="server" ErrorMessage="RequiredFieldValidator" 
ControlToValidate="txtValidateGroup" 
ValidationGroup="valGroup1"></asp:RequiredFieldValidator> 
                 
 
<asp:Button ID="Button1" runat="server" Text="Button" 
ValidationGroup="valGroup2" /> 
 
</div>

---

## Trang 28

Bài giảng Lập trình Web Aspx 
Demo Validator control 
Form Đăng ký thành viên, validation: 
Tên đăng nhập: không rỗng 
Mật khẩu và Xác nhận mật khẩu: phải giống nhau 
Email: chuẩn dạng email 
MSSV: chuôi 7 ký tự số 
Khóa: 2005-2030 
28 
GV biên soạn: Trần Kim Hương

---

## Trang 29

Bài giảng Lập trình Web Aspx 
Demo Validator control 
Form Đăng ký thành viên, validation: 
29 
GV biên soạn: Trần Kim Hương

---

## Trang 30

Bài giảng Lập trình Web Aspx 
NỘI DUNG 
30 
tkhuong@dthu.edu.vn 
Validator Control 
Web User Control

---

## Trang 31

Bài giảng Lập trình Web Aspx 
Web User Controls 
Khi kết hợp các control để tạo thành một control mới gọi là 
Web User Controls (UC) 
Sử dụng UC cũng tương tự như sử dụng thủ tục hoặc hàm  
 
 khả năng tái sử dụng UC trên các trang web 
31 
GV biên soạn: Trần Kim Hương

---

## Trang 32

Bài giảng Lập trình Web Aspx 
Tạo Web User Controls 
R-click thư mục 
chứa  Add  
Add New Item 
 Web User 
Control (Web) 
32 
GV biên soạn: Trần Kim Hương

---

## Trang 33

Bài giảng Lập trình Web Aspx 
Tạo Web User Controls 
Tạo User Controls 
Tập tin lưu trữ giao diện UC có phần mở rộng là .ascx và lưu trữ 
code là ascx.cs 
Thiết kế: giống như thiết kế trên trang aspx 
Điểm khác biệt với trang aspx: 
• Thay thế tag định hướng <%@ Page…%> bằng tag <%@ 
Control…%> 
• Không có tag <html></html> và <body></body> 
 
33 
GV biên soạn: Trần Kim Hương

---

## Trang 34

Bài giảng Lập trình Web Aspx 
Sử dụng Web User Controls 
Sử dụng User Controls (2 cách) 
Cách 1. 
• Kéo và thả UC vào trang aspx 
• Lúc đó, trong trang aspx sẽ xuất hiện tag định hướng <%@ 
Register…%> 
Cách 2. 
• Cấu hình trong tập tin web.config 
• Cú pháp 
36 
GV biên soạn: Trần Kim Hương

---

## Trang 35

Bài giảng Lập trình Web Aspx 
Sử dụng Web User Controls 
Sử dụng User Controls (2 cách) 
Cách 2. 
• Ví dụ 
37 
GV biên soạn: Trần Kim Hương

---

## Trang 36

Bài giảng Lập trình Web Aspx 
Load động User Controls 
Khi nào load động User Controls? 
Trong một trang aspx có yêu cầu sử dụng nhiều uc trên cùng 
một vị trí của trang 
Bài toán thường gặp 
• Khi chuỗi tham số của đối tượng Request thay đổi 
Các bước thực hiện trên trang aspx 
Tạo điều khiển Panel hoặc PlaceHolder 
Trong phương thức Page_Load, viết đoạn code sau: 
39 
GV biên soạn: Trần Kim Hương

---

## Trang 37

Bài giảng Lập trình Web Aspx 
Load động User Controls 
Giới thiệu điều khiển Panel và PlaceHolder 
Được sử dụng để chứa các điều khiển khác 
Điều khiển Panel cho phép đặt những điều khiển khác vào bên 
trong lúc thiết kế còn PlaceHolder thì không 
Xử lý thêm một điều khiển khác vào lúc thực thi: 
 
 
 
Ví dụ: thêm điều khiển TextBox vào Panel pnNoidung 
40 
GV biên soạn: Trần Kim Hương

---

## Trang 38

Bài giảng Lập trình Web Aspx 
Lập trình sử dụng User Control lúc runtime 
Khai báo PlaceHolder để chứa User Control 
 <asp:PlaceHolder ID="PlaceHolder1" 
runat="server"></asp:PlaceHolder> 
 
Lập trình load User Control vào PlaceHolder 
41 
GV biên soạn: Trần Kim Hương 
 protected void Page_Load(object sender, EventArgs e) 
        { 
            var ct1 = Page.LoadControl("MyControl.ascx"); 
            PlaceHolder1.Controls.Add(ct1);            
        }

---

## Trang 39

Bài giảng Lập trình Web Aspx 
Demo Web User Control 
Tạo: R-click project  Add  New Item  Web Form User Control 
(Web)  Name: LoginControl.ascx 
Biên dịch 
Sử dụng: trang Default.aspx  kéo thả LoginControl.ascx vào 
Mặc định User control không có thuộc tính nào  muốn thiết lập giá 
trị mặc định: vào class LoginControl thiết lập thuộc tính (kéo thả lại 
để thấy thuộc tính mới thiết lập) 
42 
GV biên soạn: Trần Kim Hương

---

## Trang 40

Bài giảng Lập trình Web Aspx 
Demo Web User Control 
43 
GV biên soạn: Trần Kim Hương

---

## Trang 41

Bài giảng Lập trình Web Aspx 
Demo Web User Control 
Cách 2: add user control vào trang web ở thời điểm thực thi 
Quy định vùng trên trang web cho user control được add vào: vd 
trang ASPNETControl.aspx  thả control PlaceHolder (chứa 
control khác, ko render trên giao diện) 
PageLoad: add user control vào 
44 
GV biên soạn: Trần Kim Hương

---

## Trang 42

Bài giảng Lập trình Web Aspx 
Demo Web User Control 
Cách 
2: 
add 
user 
control vào trang web ở 
thời điểm thực thi 
45 
GV biên soạn: Trần Kim Hương

---

## Trang 43

Bài giảng Lập trình Web Aspx 
Tổng kết 
Validation Controls 
Web User Controls 
46 
GV biên soạn: Trần Kim Hương

---

## Trang 44

tkhuong@dthu.edu.vn

---

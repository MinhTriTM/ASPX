# Chapter_1_1_TongQuan_Web

> **Nguồn tài liệu**: Chapter_1_1_TongQuan_Web.pdf
> **Tổng số trang**: 34

## Mục lục nhanh

- [Trang 1: ThS. TRẦN KIM HƯƠNG – KHOA CNS&KT](#trang-1)
- [Trang 2: Bài giảng Lập trình web ASPX](#trang-2)
- [Trang 3: Bài giảng Lập trình web ASPX](#trang-3)
- [Trang 4: Bài giảng Lập trình web ASPX](#trang-4)
- [Trang 5: Bài giảng Lập trình web ASPX](#trang-5)
- [Trang 6: Bài giảng Lập trình web ASPX](#trang-6)
- [Trang 7: Bài giảng Lập trình web ASPX](#trang-7)
- [Trang 8: Bài giảng Lập trình web ASPX](#trang-8)
- [Trang 9: Bài giảng Lập trình web ASPX](#trang-9)
- [Trang 10: Bài giảng Lập trình web ASPX](#trang-10)
- [Trang 11: Bài giảng Lập trình web ASPX](#trang-11)
- [Trang 12: Bài giảng Lập trình web ASPX](#trang-12)
- [Trang 13: Bài giảng Lập trình web ASPX](#trang-13)
- [Trang 14: Bài giảng Lập trình web ASPX](#trang-14)
- [Trang 15: Bài giảng Lập trình web ASPX](#trang-15)
- [Trang 16: Bài giảng Lập trình web ASPX](#trang-16)
- [Trang 17: Bài giảng Lập trình web ASPX](#trang-17)
- [Trang 18: Bài giảng Lập trình web ASPX](#trang-18)
- [Trang 19: Bài giảng Lập trình web ASPX](#trang-19)
- [Trang 20: Bài giảng Lập trình web ASPX](#trang-20)
- [Trang 21: Bài giảng Lập trình web ASPX](#trang-21)
- [Trang 22: Bài giảng Lập trình web ASPX](#trang-22)
- [Trang 23: Bài giảng Lập trình web ASPX](#trang-23)
- [Trang 24: Bài giảng Lập trình web ASPX](#trang-24)
- [Trang 25: Bài giảng Lập trình web ASPX](#trang-25)
- [Trang 26: Bài giảng Lập trình web ASPX](#trang-26)
- [Trang 27: Bài giảng Lập trình web ASPX](#trang-27)
- [Trang 28: Bài giảng Lập trình web ASPX](#trang-28)
- [Trang 29: Bài giảng Lập trình web ASPX](#trang-29)
- [Trang 30: Bài giảng Lập trình web ASPX](#trang-30)
- [Trang 31: Bài giảng Lập trình web ASPX](#trang-31)
- [Trang 32: Bài giảng Lập trình web ASPX](#trang-32)
- [Trang 33: Bài giảng Lập trình web ASPX](#trang-33)
- [Trang 34: tkhuong@dthu.edu.vn](#trang-34)

---

## Trang 1

ThS. TRẦN KIM HƯƠNG – KHOA CNS&KT
tkhuong@dthu.edu.vn
Chương 1.
TỔNG QUAN INTERNET & WEB

---

## Trang 2

Bài giảng Lập trình web ASPX
NỘI DUNG
❖Giới thiệu tổng quan ASP.NET
❖Làm việc với Web Form & Controls
❖Cấu hình giao diện Website
❖Làm việc với CSDL
❖Quản lý trạng thái
❖Bảo mật ứng dụng Web
❖Triển khai ứng dụng Web
2
tkhuong@dthu.edu.vn

---

## Trang 3

Bài giảng Lập trình web ASPX
Lịch sử Internet
❖Mạng Internet xuất phát từmạng
ARPANET của Mỹ(1969) – mạng
giữa các trường Đại học
❖1989 - Tim Berners-Lee phát minh 
ra giao thức World Wide Web, sau 
đó tạo ra ngôn ngữ Hypertext 
Markup Language – HTML
❖25/12/1990 – Tim viết trình duyệt 
(Web Browser) và Web server đầu 
tiên (CERN HTTPd)
❖Từ năm 1993 Internet phát triển rất 
nhanh
❖Việt nam có Internet vào tháng 
11/1997
3
GV biên soạn: Trần Kim Hương

---

## Trang 4

Bài giảng Lập trình web ASPX
Internet là gì?
❖Internet là tập hợp các máy tính kết nối mạng trên thế giới trao đổi 
thông tin với nhau thông qua giao thức TCP/IP (Transmission 
Control Protocol/ Internet Protocol)
❖Mang lại rất nhiều tiện ích hữu dụng cho người sử dụng, nổi bật 
nhất là dịch vụ thư điện tử (email), trò chuyện trực tiếp (chat) và truy 
tìm dữ liệu (search engine,…)
❖Dịch vụ được dùng rất phổ biến trên Internet là World Wide Web 
(WWW, thường được gọi tắt là Web)
4
GV biên soạn: Trần Kim Hương

---

## Trang 5

Bài giảng Lập trình web ASPX
Web là gì?
❖Web là các dịch vụ phân tán cung cấp thông tin 
multimedia dựa trên hypertext
▪Phân tán: thông tin được đặt trên nhiều máy chủ
khắp thế giới
▪Multimedia: thông tin bao gồm text, graphics, sound, 
video
▪Hypertext: là kỹthuật được sửdụng đểtruy cập
thông tin
5
GV biên soạn: Trần Kim Hương

---

## Trang 6

Bài giảng Lập trình web ASPX
Website trên thế giới
❖In the December 2023 survey we received responses from 
1,088,057,023 sites across 269,268,434 domains and 
12,355,610 web-facing computers. This reflects a loss of 4.1 
million sites, an increase of 238,593 domains, and a loss of 
128,028 web-facing computers.
6
GV biên soạn: Trần Kim Hương
https://www.netcraft.com/blog/december-2023-web-server-survey/

---

## Trang 7

Bài giảng Lập trình web ASPX
Website trên thế giới
7
GV biên soạn: Trần Kim Hương
https://www.netcraft.com/blog/december-2023-web-server-survey/

---

## Trang 8

Bài giảng Lập trình web ASPX
Website trên thế giới
8
GV biên soạn: Trần Kim Hương
https://www.netcraft.com/blog/december-2023-web-server-survey/

---

## Trang 9

Bài giảng Lập trình web ASPX
Sơ đồ vận hành của website
10
GV biên soạn: Trần Kim Hương
https://nentang.vn

---

## Trang 10

Bài giảng Lập trình web ASPX
Sơ đồ vận hành của website
11
GV biên soạn: Trần Kim Hương

---

## Trang 11

Bài giảng Lập trình web ASPX
Các khái niệm cơ bản
❖Web server
▪Máy chủ cài đặt các phần mềm phục vụ các ứng dụng 
web
▪Webserver có khả năng tiếp nhận request từ các trình 
duyệt web và gửi phản hồi đến client thông qua giao thức 
HTTP hoặc các giao thức khác
▪Có nhiều web server khác nhau như: Apache, Nginx,
IIS,…
12
GV biên soạn: Trần Kim Hương

---

## Trang 12

Bài giảng Lập trình web ASPX
Web Server
13
GV biên soạn: Trần Kim Hương

---

## Trang 13

Bài giảng Lập trình web ASPX
Các khái niệm cơ bản
❖Web client
▪Máy tính (client) dùng để truy xuất các trang web
▪Có khả năng yêu cầu và nhận kết quả từ Web server
14
GV biên soạn: Trần Kim Hương

---

## Trang 14

Bài giảng Lập trình web ASPX
Các khái niệm cơ bản (2)
❖Web Browser – trình duyệt web
▪Phần mềm dùng để xem các tài liệu hoặc tìm kiếm các tài 
nguyên trên Word Wide Web
▪Hiển thị các loại tài nguyên khác nhau: text, gif, jpeg, 
sound, video,….
▪Hỗ trợ nhiều giao thức: HTTP, FTP, SMTP, POP,…
▪Có thể “plug-in” các công cụ vào browser để tăng tính 
năng (color, 3D animation,…)
15
GV biên soạn: Trần Kim Hương

---

## Trang 15

Bài giảng Lập trình web ASPX
Các khái niệm cơ bản (2)
❖Một số trình duyệt phổ biến hiện nay
16
GV biên soạn: Trần Kim Hương

---

## Trang 16

Bài giảng Lập trình web ASPX
Các khái niệm cơ bản (3)
❖Web = Protocol + language + naming infrastructure
❖HTTP– HyperText Transfer Protocol
▪Là giao thức chuyển giao siêu văn bản trên web
▪Giao thức này là tập hợp các quy định dùng để trao đổi các tài liệu (văn 
bản, hình ảnh, âm thanh, video, các tập tin đa truyền thông,…) giữa 
Web server và Web browser
❖HTML – HyperText Markup Language
▪Ngôn ngữ dùng để xây dựng các trang web
▪Gồm các tag giúp web browser biết cách định dạng thông tin hiển thị
❖URL – Uniform Resource Locator
▪Đường dẫn chỉ tới trang web cụ thể trên internet
▪Cú pháp: scheme://<host>[port:] [path [?<querystring>] ]
17
GV biên soạn: Trần Kim Hương

---

## Trang 17

Bài giảng Lập trình web ASPX
Các khái niệm cơ bản (3)
❖URL – Uniform Resource Locator
18
GV biên soạn: Trần Kim Hương

---

## Trang 18

Bài giảng Lập trình web ASPX
Dịch vụ www (world wide web)
❖Dịch vụ Email, FTP, Chat
▪Thư điện tử - Email (Electronic mail)
• Là dịch vụ trao đổi thông tin qua mạng viễn thông
• Sử dụng giao thức SMTP/ POP3 để gửi nhận email
• Địa chỉ email có dạng: name@domain (tkhuong@dthu.edu.vn)
• Được quản lý bởi Mail Server
• Phân biệt Webmail với Mail Client
▪Truyền tải tập tin – FTP (File Transfer Protocol
• Là dịch vụ trao đổi các tập tin giữa các máy tính trên internet
▪Chat
• Skype, zalo, facebook, what apps,….
19
GV biên soạn: Trần Kim Hương

---

## Trang 19

Bài giảng Lập trình web ASPX
Một số thuật ngữ kỹ thuật khác (1)
❖Internet: Mạng máy tính toàn cầu kết nối các máy tính 
khắp nơi trên thế giới. Tập các giao thức được dùng gọi 
chung là TCP/IP.
❖Intranet: Mạng cục bộ có kiến trúc tương tự mạng 
Internet
❖Website: Tập hợp các trang web. Website của các tổ 
chức hay cá nhân trên mạng bao gồm tập các trang web 
liên quan đến tổ chức này.
❖Webpage: là trang web, có thể hiển thị các thông tin 
dưới dạng văn bản, hình ảnh, âm thanh,…
20
GV biên soạn: Trần Kim Hương

---

## Trang 20

Bài giảng Lập trình web ASPX
Một số thuật ngữ kỹ thuật khác (2)
❖Homepage: Trang chủ, thường là trang đầu tiên (mặc 
định) khi truy cập một website.
❖Hyperlink: siêu liên kết, dùng để liên kết các trang web 
và dịch vụ của các website trên Internet
❖IAP (Internet Access Provider): Nhà cung cấp đường 
truyền Internet
❖ISP (Internet Service Provider): Nhà cung cấp dịch vụ 
Internet. Một số ISP hiện nay ở VN: Viettel, VNPT, 
FPT,…
21
GV biên soạn: Trần Kim Hương

---

## Trang 21

Bài giảng Lập trình web ASPX
Một số thuật ngữ kỹ thuật khác (3)
❖Search engines: Máy tìm kiếm, thông dụng hiện nay: 
Google, Bing, Yahoo,…
❖HTTP, FTP, SMTP, POP3,…: Đây là các giao thức được 
sử dụng cho các dịch vụ web, ftp, email trên internet
23
GV biên soạn: Trần Kim Hương

---

## Trang 22

Bài giảng Lập trình web ASPX
Web 1.0 vs Web 2.0 vs Web 3.0 vs Web 4.0
25
GV biên soạn: Trần Kim Hương

---

## Trang 23

Bài giảng Lập trình web ASPX
26
GV biên soạn: Trần Kim Hương

---

## Trang 24

Bài giảng Lập trình web ASPX
Web 1.0
❖Website 1.0 là phiên bản đầu tiên của trang web, hoạt
động chỉởdạng văn bản và hình ảnh cốđịnh, cho phép
lượng lớn người dùng truy cập các dữkiện, thông tin và
nội dung từcác nguồn.
❖4 yếu tố thiết kế trang web 1.0
▪Trang tĩnh.
▪Nội dung được phục vụtừhệthống tệp của máy chủ.
▪Các trang được xây dựng bằng Server Side hoặc Giao
diện cổng chung (CGI).
▪Khung và Bảng được sửdụng đểđịnh vịvà căn chỉnh các
thành phần trên một trang.
27
GV biên soạn: Trần Kim Hương

---

## Trang 25

Bài giảng Lập trình web ASPX
28
GV biên soạn: Trần Kim Hương

---

## Trang 26

Bài giảng Lập trình web ASPX
Web 2.0
❖Website 2.0 hay còn gọi là web xã hội, "ra đời" nhằm mục đích làm
nổi bật nội dung do người dùng tạo, mang đến khảnăng sửdụng
và sựtương tác tuyệt vời cho người dùng cuối.
❖Công nghệphát triển website 2.0 bao gồm khung AJAX và
JavaScript.
❖5 tính năng chính của Web 2.0
▪Phân loại thông tin miễn phí, cho phép người dùng truy xuất và phân
loại thông tin chung.
▪Nội dung động đáp ứng đầu vào của người dùng.
▪Luồng thông tin giữa chủsởhữu trang web và người dùng trang web
bằng phương tiện đánh giá và nhận xét trực tuyến.
▪API được phát triển đểcho phép tựsửdụng, chẳng hạn như bởi một
ứng dụng phần mềm.
▪Truy cập web dẫn đến mối quan tâm khác nhau, từcơ sởngười dùng
Internet truyền thống đến nhiều người dùng hơn.
29
GV biên soạn: Trần Kim Hương

---

## Trang 27

Bài giảng Lập trình web ASPX
30
GV biên soạn: Trần Kim Hương

---

## Trang 28

Bài giảng Lập trình web ASPX
Web 3.0
❖Website 3.0 hay Semantic Web, phát triển việc sử dụng và tương tác 
web, gồm việc thay đổi web thành CSDL, cho phép nâng cấp back-end 
của web (thay vì tập trung vào front-end như web 2.0)
❖Web 3.0 là một thuật ngữđược sửdụng đểmô tảnhiều diễn biến về
việc sửdụng và tương tác web giữa một sốđường dẫn →dữliệu không
được sởhữu mà thay vào đó được chia sẻ, nơi các dịch vụhiển thịcác
chếđộxem khác nhau cho cùng một trang web / cùng một dữliệu.
❖5 tính năng chính Web 3.0
▪Semantic Web: chia sẻ, kết nối nội dung thông qua tìm kiếm và phân tích ý 
nghĩa của từ
▪Trí tuệnhân tạo: khả năng xử lý ngôn ngữ tự nhiên
▪Đồhọa 3D
▪Kết nối: thông tin được kết nối nhiều hơn nhờsiêu dữliệu ngữnghĩa
▪Nội dung Ubiquity có thểtruy cập bằng nhiều ứng dụng, mọi thiết bịđược kết
nối với web, các dịch vụcó thểđược sửdụng ởmọi nơi.
31
GV biên soạn: Trần Kim Hương

---

## Trang 29

Bài giảng Lập trình web ASPX
32
GV biên soạn: Trần Kim Hương

---

## Trang 30

Bài giảng Lập trình web ASPX
Web 4.0
❖Website 4.0 sử dụng các công nghệ như thực tế ảo, trí 
tuệ nhân tạo,… để tạo ra 1 trải nghiệm mượt mà và 
chân thực cho người dùng.
❖Tuy nhiên vẫn chưa được định nghĩa rõ ràng và cụ thể, 
các chuyên gia cho rằng Web 4.0 có thể sẽ tập trung 
vào việc kết nối và phân tán hơn so với web 3.0, gồm 
các công nghệ tiên tiến như blockchain và bitcoin 
33
GV biên soạn: Trần Kim Hương

---

## Trang 31

Bài giảng Lập trình web ASPX
Xem video
❖Lịch sử internet
▪https://youtu.be/9hIQjrMHTv4
❖Evolution Web 1.0, Web 2.0, Web 3.0
▪https://youtu.be/bsNcjya56v8
❖The Future Internet: Service Web 3.0
▪https://youtu.be/off08As3siM
❖A Story about the Semantic Web
▪https://vimeo.com/11529540
❖Transformatic Digital Web 4.0
▪https://vimeo.com/207440932
34
GV biên soạn: Trần Kim Hương
https://ahmadfaizar.blogspot.com/2018/08/evolution-of-web-web-10-web-20-web-30.html

---

## Trang 32

Bài giảng Lập trình web ASPX
Các bước để xây dựng 1 website
1. Xác định yêu cầu website
2. Mua tên miền
3. Thiết kế website
4. Thuê chỗ hosting
5. Đưa vào hoạt động
6. Duy trì thông tin, bảo dưỡng website
35
GV biên soạn: Trần Kim Hương

---

## Trang 33

Bài giảng Lập trình web ASPX
Bài tập thực hành
❖Thiết lập nhóm để trao đổi
▪Sử dụng Google group
▪Skype
▪Slack
▪….
❖Khảo sát các dịch vụ hosting miễn phí hỗ trợ 
ASP.NET
36
GV biên soạn: Trần Kim Hương

---

## Trang 34

tkhuong@dthu.edu.vn
DISCUSSION!

---

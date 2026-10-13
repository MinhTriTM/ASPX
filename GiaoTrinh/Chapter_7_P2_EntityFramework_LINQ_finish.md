# Chapter_7_P2_EntityFramework_LINQ_finish

> **Nguồn tài liệu**: Chapter_7_P2_EntityFramework_LINQ_finish.pdf
> **Tổng số trang**: 23

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
- [Trang 23: tkhuong@dthu.edu.vn](#trang-23)

---

## Trang 1

Biên soạn: ThS. TRẦN KIM HƢƠNG 
tkhuong@dthu.edu.vn 
Chương
Chƣơng 
 7.2
7.2 
 
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
Outline 
LINQ là gì 
Cú pháp truy vấn LINQ 
Các phƣơng thức LINQ to Entity 
Hƣớng dẫn thực hành LINQ to Entity 
Bài tập thực hành LINQ to Entity 
Bài tập thực hành Xây dựng website BookShop 
Online 
 
 
2 
tkhuong@dthu.edu.vn

---

## Trang 3

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
What is LINQ? 
LinQ (Language Integrated Query) là cú pháp truy vấn có cấu trúc 
được xây dựng trong C# để truy xuất dữ liệu từ các nguồn dữ liệu 
khác nhau như collections, ADO.NET DataSet, XML Docs, web 
service, MS SQL Server và các database khác. 
 
4 
tkhuong@dthu.edu.vn

---

## Trang 4

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Kiến
 trúc
 LINQ
 
Kiến trúc LINQ 
5 
tkhuong@dthu.edu.vn

---

## Trang 5

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Example LINQ to Object 
EX1. Using foreach in List 
6 
tkhuong@dthu.edu.vn

---

## Trang 6

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Example LINQ to Object 
EX2. Using LINQ 
7 
tkhuong@dthu.edu.vn

---

## Trang 7

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Why LINQ? 
Advantages of LINQ 
Ngôn ngữ quen thuộc: không phải học ngôn ngữ truy vấn mới cho 
từng nguồn dữ liệu khác nhau. 
Ít code: giảm số lượng code được viết so với truy vấn truyền 
thống 
Code dễ đọc: code đơn giản, rõ ràng, dễ hiểu 
Chuẩn hóa để truy vấn nhiều nguồn dữ liệu: dùng 1 cú pháp LINQ 
để truy vấn trên nhiều nguồn dữ liệu khác nhau. 
Biên dịch an toàn: nó kiểm tra kiểu của đối tượng tại thời điểm 
biên dịch. 
9 
tkhuong@dthu.edu.vn

---

## Trang 8

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ to Entity 
Có 2 cách viết câu truy vấn LINQ 
 
10 
tkhuong@dthu.edu.vn 
private NewsEntities _dbcontext = new NewsEntities(); 
* LINQ Method Synax 
public ActionResult GetArticleByAuthor(string authorId) 
{ 
    var result = _dbcontext.BaiViets.Where(x => x.MaTG == 
authorId).ToList(); 
    return View(result); 
} 
* LINQ Query Synax 
public ActionResult GetArticleByAuthor1(string authorId) 
        { 
            var result = from news in _dbcontext.BaiViets 
                         where news.MaTG == authorId 
                         select news; 
            return View(result); 
        }

---

## Trang 9

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Query Syntax 
LINQ có 2 cú pháp truy vấn là Query syntax và Method syntax, sử 
dụng thư viện System.Linq 
LINQ Query Syntax 
 
 
 
Ví dụ 
 
11 
tkhuong@dthu.edu.vn 
var lists = from <Biến lưu thông tin từng phần tử> in <Nguồn dữ liệu> 
[<Phép toán truy vấn: where, join ... in, order by...> Biều thức lambda] 
select <Biến lưu thông tin từng phần tử> 
private DBQLNVDataContext _dbContext = new DBQLNVDataContext(); 
var result = from nv in _dbContext.NhanViens 
                         select nv; 
            dgvNV.DataSource = result; 
https://www.tutorialspoint.com/linq/linq_query_operators.htm

---

## Trang 10

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Query Syntax 
Ví dụ 
 
12 
tkhuong@dthu.edu.vn 
var result = from nv in _dbContext.NhanViens 
             select nv;          
var result = from nv in _dbContext.NhanViens 
 
 
where nv.MaCV == "P" 
 
 
select new 
               { 
 
 
 
MaNhanVien = nv.MaNV, 
                      hotenNV = nv.HoNV, 
                      tenNV = nv.TenNV, 
                      luong = nv.Luong, 
                      maCV = nv.MaCV, 
}; 
private DBQLNVDataContext _dbContext = new DBQLNVDataContext();

---

## Trang 11

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Query Syntax 
Ví dụ. Linq join table  
 
13 
tkhuong@dthu.edu.vn 
private DBQLNVDataContext _dbContext = new DBQLNVDataContext(); 
 var result = from nv in _dbContext.NhanViens 
              join cv in _dbContext.ChucVus on nv.MaCV equals cv.MaCV 
              join bp in _dbContext.Bophans on nv.MaBP equals bp.MaBP 
              select new 
              { 
                   hoNV = nv.HoNV, 
                   tenNV = nv.TenNV, 
                   luong = nv.Luong, 
                   chucVu = cv.TenCV, 
                   boPhan = bp.TenBP, 
               };

---

## Trang 12

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Query Syntax 
Ví dụ. Linq Left join table  
 
14 
tkhuong@dthu.edu.vn 
private DBQLNVDataContext _dbContext = new DBQLNVDataContext(); 
var result = from nv in _dbContext.NhanViens 
             join cv in _dbContext.ChucVus on nv.MaCV equals cv.MaCV 
 
 
 
into nv_cv 
             join bp in _dbContext.Bophans on nv.MaBP equals bp.MaBP 
 
 
 
into nv_bp 
             from nc in nv_cv.DefaultIfEmpty() 
             from nb in nv_bp.DefaultIfEmpty() 
             select new 
             {  
 
 
 
              tenNV = nv.TenNV, 
 
 
chucVu = nc != null ? nc.TenCV : "", 
 
 
boPhan = nb != null ? nb.TenBP : "", 
               Fullname = nv.HoNV + " " + nv.TenNV 
             };

---

## Trang 13

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Extension Methods (1) 
15 
tkhuong@dthu.edu.vn 
https://www.entityframeworktutorial.net/querying-entity-graph-in-entity-framework.aspx

---

## Trang 14

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Extension Methods (2) 
The following are some of the standard query operators 
(or extension methods) that can be used with LINQ-to-
Entities queries. 
16 
tkhuong@dthu.edu.vn 
LINQ Extension Methods 
.Where(e=>đk) 
.GroupBy(e=>bthuc) 
.OrderBy(e=>bthuc)/ 
.OderByDescending 
.Take(sluong)/ 
.TakeWhile(e=>đk) 
.Skip(sluong)/ 
.SkipWhile(e=>đk) 
.Single(e=>đk)/ 
.SingleOrDefault() 
.First()/ FirstOrDefault() .Last()/ LastOrDefault() 
.Find() 
.ToList() 
.Count(e=>bthuc) 
.Min() 
.Max() 
.Average() 
.Sum()

---

## Trang 15

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Method Syntax 
17 
tkhuong@dthu.edu.vn 
VD.

---

## Trang 16

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Method Syntax 
18 
tkhuong@dthu.edu.vn 
VD. GroupBy

---

## Trang 17

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Method Syntax 
19 
tkhuong@dthu.edu.vn 
VD. GroupBy 

The above query will execute the following database query: 
SELECT [Project2].[C1] AS [C1],  
 
[Project2].[StandardId] AS [StandardId],  
 
[Project2].[C2] AS [C2],  
 
[Project2].[StudentID] AS [StudentID],  
 
[Project2].[StudentName] AS [StudentName],  
 
[Project2].[StandardId1] AS [StandardId1]  
FROM ( SELECT [Distinct1].[StandardId] AS [StandardId],  
 
1 AS [C1], [Extent2].[StudentID] AS [StudentID],  
 
[Extent2].[StudentName] AS [StudentName],  
 
[Extent2].[StandardId] AS [StandardId1],  
 
CASE WHEN ([Extent2].[StudentID] IS NULL) THEN CAST(NULL AS int) ELSE 1 END AS [C2]  
 
FROM (SELECT DISTINCT [Extent1].[StandardId] AS [StandardId]  
 
 
FROM [dbo].[Student] AS [Extent1] ) AS [Distinct1]  
 
 
LEFT OUTER JOIN [dbo].[Student] AS [Extent2] ON ([Distinct1].[StandardId] = 
[Extent2].[StandardId]) OR (([Distinct1].[StandardId] IS NULL) AND ([Extent2].[StandardId] IS NULL))  
) AS [Project2]  
ORDER BY [Project2].[StandardId] ASC, [Project2].[C2] ASC

---

## Trang 18

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ To Entity Framework 
20 
tkhuong@dthu.edu.vn 
Chú ý 
Sử dụng cách thực thi này sẽ giúp: 
+ Cải thiện hiệu năng vì chỉ thực thi một lần. 
+ Dữ liệu trả về là mới nhất.

---

## Trang 19

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ To Entity Framework 
21 
tkhuong@dthu.edu.vn 
Chú ý: có 2 kịch bản truy vấn 
Trì hoãn thực thi: where, việc thực thi truy vấn chỉ khi thực hiện 
foreach 
Thực thi ngay lập tức (Immediate Execution): thực thi ngay lập 
tức câu lệnh và trả về kết quả. Để thực thi ngay lập tức, chúng ta 
có thể dùng những toán tử chuyển đổi như ToList, ToArray, 
ToDictionary... hoặc những toán tử thành phần như First, 
FirstOrDefault, Last, LastOrDefault...

---

## Trang 20

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
LINQ Extension Methods (3) 
Cú pháp Cập nhật dữ liệu trong LinQ to Entity 
Framework 
22 
tkhuong@dthu.edu.vn 
LINQ Extension Methods 
Function 
Syntax 
Example 
Insert data 
.Add (object) 
_contextDB.Nhanviens.Add(nv1) 
Edit data 
.Update<table>(object) 
_contextDB.Update<Nhanviens>(nv1) 
Delete data 
.Remove(object) 
_contextDB.NhanViens.Remove(nv1) 
Save database: db.SaveChanges()

---

## Trang 21

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Hƣớng dẫn thực hành LINQ to Entity 
Sử dụng EF theo mô hình Database First và DB News 
1.
Restore DB News 
2.
Setup Entity Framework 
3.
Tạo Entity Framework sử dụng mô hình DB First 
4.
Tạo ADO.NET Data Model 
5.
Tạo mới Form thao tác với table Bài viết 
1.
Lấy danh sách tất cả bài viết 
2.
Lấy danh sách bài viết thuộc thể loại TL02 
3.
Lấy 5 bài viết mới nhất 
Tạo mới Controller thao tác với table Thể loại 
Insert thể loại sách mới 
Edit thể loại sách 
Delete thể loại sách 
 
23 
tkhuong@dthu.edu.vn

---

## Trang 22

Web Technology with ASP.NET MVC 
Web Technology with ASP.NET MVC 
Bài thực hành LINQ to Entity 
Thực hiện tương tự như Demo 
Thao tác với table Tác giả 
Hiển thị danh sách tác giả 
Lấy 3 tác giả đầu tiên trong danh sách đã sắp xếp giảm dần theo 
NickName 
Hiển thị danh sách bài viết của tác giả TG01 (sắp xếp giảm dần 
theo ngày đăng 
Insert tác giả mới vào danh sách 
Edit thông tin tác giả 
Xóa thông tin tác giả 
 
24 
tkhuong@dthu.edu.vn

---

## Trang 23

tkhuong@dthu.edu.vn

---

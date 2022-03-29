"# Analyze-college-Test-scores-HCM-city" 


Data Science – Phân tích điểm thi đại học tại thành phố hồ chí minh năm 2020
1.	Data mining : 
-	Công cụ sử dụng : python 
-	Web site : http://diemthi.hcm.edu.vn/
-	Sử dụng thư viện : subprocess
-	Số lượng data : 75,000 dòng (02000001 - > … )
Start = 2000001
End = 2074719



![image](https://user-images.githubusercontent.com/102569475/160673015-ffa04db2-fd94-49fa-887c-c656cb03e469.png)



2.	Clean HTML data manually:

a.	Sử dụng string manipulation

b.	Sử dụng file unicode ( utf-8) lấy từ https://www.utf8-chartable.de/ để encode cho dữ liệu

-	Sử dụng file: decode.txt để lấy char và code để xử lý unicode trong bài => được file unicode.txt


sbd,name,dd,mm,yy,toán,ngữ văn,khxh,khtn,lịch sử,địa lí,gdcd,sinh học,vật lí,hóa học,tiếng anh,tiếng nhật,tiếng pháp,tiếng trung,tiếng đức,tiếng nga
![image](https://user-images.githubusercontent.com/102569475/160673166-87e25afc-0750-4985-9861-a37d5bb39cea.png)

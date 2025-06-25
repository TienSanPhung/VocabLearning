# # 📚 VocaLearning – ASP.NET Vocabulary Learning App

**VocaLearning** là một ứng dụng web giúp người học tiếng Anh nâng cao vốn từ vựng thông qua các bài học chủ đề, flashcards và quiz tương tác. Dự án được xây dựng bằng **ASP.NET Core**, phù hợp cho cả học sinh, sinh viên và người đi làm muốn cải thiện kỹ năng ngôn ngữ.

## 🚀 Tính năng

- Danh sách từ vựng theo chủ đề (Business, Travel, Academic, v.v...)
- Flashcards giúp ghi nhớ nhanh
- Quiz kiểm tra từ vựng với kết quả tức thì
- Giao diện thân thiện, responsive (tương thích điện thoại)

## 🛠️ Công nghệ sử dụng

- ASP.NET Core MVC
- Entity Framework Core (code-first)
- SQL Server
- Bootstrap 5

## ⚙️ Cài đặt local

```bash
# Clone project
git clone https://github.com/yourusername/VocaLearning.git
cd VocaLearning

# Khôi phục packages
dotnet restore

# Cập nhật database (migration)
dotnet ef database update

# Chạy ứng dụng
dotnet run

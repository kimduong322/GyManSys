1. Clone project
2. Install Maven for Intellij or Elcipse
3. Cài đặt MySQL
4. Vào file 
gym-management-system\src\main\resources\application.yml
Sửa tên database, password cho giống với database trên local
(Phần này là cần cài đặt password cho root user và password trong file cấu hình là giống nhau)
5. Vào file gym-management-system\gym_management_system.sql
Chạy script trên database ở local
6. Maven build/ Run as configuration với Goals là : spring-boot:run

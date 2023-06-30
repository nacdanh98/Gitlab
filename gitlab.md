## Cập nhật tính năng mới Gitlab Community 16.0
### 1. Comment templates
  - Tính năng cho phép tạo comment template khi cần dùng nhận xét đó nhiều lần khi comment issue , Merge requests, diff, Work items.
  - Khi comment chỉ cần click vào biểu tượng comment
    ![image](https://github.com/nacdanh98/Gitlab/assets/49748262/d64e7fc0-fd2a-4baf-8bbb-9fbde25c93bb)

### 2. Cho phép cập nhật Fork trên Gitlab UI
    ![image](https://github.com/nacdanh98/Gitlab/assets/49748262/9f385f64-15e2-4ca4-b0af-a6d3a83ad11e)

### 3. Trải nghiệm Web IDE trên UI
    ![image](https://github.com/nacdanh98/Gitlab/assets/49748262/3d16dc98-2f33-4e9e-8928-b3673dd66e07)
### 4. Token rotation API
    Chủ sở hữu mã token có thể sử dụng :rotate ở cuối API để xoay vòng mã token truy cập cá nhân, nhóm và dự án theo chương trình.
```
  POST /personal_access_tokens/:id/rotate
```
### 5. Self-managed GitLab kết nối tới 2 database 
  - Tạo ra 1 database riêng cho các tính năng CI
  - Áp dụng với các phương thức cài đặt GitLab, GitLab Helm chart, GitLab Operator, GitLab Docker images, và installation from source.

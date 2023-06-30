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
### 6. Đặt rate limit với người dùng chưa được xác thực API
### 7. GitLab chart improvements
  - Postgre SQL support version từ 13 trở lên
  - Phiển bản helm thấp nhất còn hỗ trợ là 3.5.2
  - GitLab Runner default version hiện tại là Ubuntu 22.04
### 8. Ra mắt MVC launch of a Maven/Gradle package importer
  - Để sử dụng tool tạo file config.yml chứa thông tin chi tiết các gói bạn muốn import vào Gitlab
  - Sau đó thêm importer vào file .gitlab-ci.yml
### 9. Tạo runner với REST API
    ![image](https://github.com/nacdanh98/Gitlab/assets/49748262/39d89545-00dd-45cc-bbc6-99af24fc0850)
### 10. Rate Limit for the projects/:id/jobs API endpoint reduced
### 11. Tạo instance runner in the Admin Area với tư cách user
### 12. Tạo  project runners voweis tư cách user
### 13. Cho phép tùy chỉnh số lượng CICD config file
### 14. Tạo  group runners voweis tư cách user
### 15. Update merge request theo thời gian thực
### 16. CI/CD components
    -  Cho phép tái sử dụng cicd pineline file
### 17. Giới hạn session cho user



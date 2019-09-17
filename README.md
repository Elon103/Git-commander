# Git commander
- **Git config**
```
git config --global user.name "John Doe"
git config --global user.email "john@example.com"
```
  global được sử dụng để áp dụng cho tất cả các projects. Nếu bạn ko sử dụng --global thì settings sẽ chỉ dùng cho riêng project đó.
- **Giúp Git bỏ qua file modes**
```
cd project/
git config core.filemode false
```
Câu lệnh trên hữu dụng khi chúng ta không cần quan tâm đến quyền truy cập files (ví dụ như khi sử dụng Windows).
- **Liệt kê những settings đang sử dụng**
```
git config --list
```
- **Khởi tạo Git repo cho code có sẵn**
```
cd existing-project/
git init
```
- **Clone một remote repo**
```
git clone https://github.com/user/repository.git
```
Câu lệnh trên sẽ tạo một thư mục mới có tên giống trên của repo.
- **Clone một remote repo tại thư mục hiện tại**
```
git clone https://github.com/user/repository.git 
```
- **Xem thông tin trợ giúp cho một câu lệnh git**
```
git help clone
```
- **Update và merge branch hiện tại với một remote repo**
```
cd repo/
git pull origin master
```
với origin là remote repo, master là remote branch.
Nếu bạn không muốn merge những thay đổi của bạn, hãy sử dụng git fetch

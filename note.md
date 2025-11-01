# git init

- chạy git vào dự án.

# git status

- xem trong folder dự án có những file nào.

# git add

- dùng để lưu 1 file tại thời điểm này.
  VD: git add index.html thì sẽ lưu index.html tại thời điểm này.
- câu lệnh để lưu tất cả file là git add .

# git reset

- xóa 1 file lưu tại thời điểm này.

# git commit

- chính thức lưu file
- cú pháp: git commit -m 'ghi chú'

# git log

- xem các thời điểm đã lưu.
- đánh để xem kết quả gọn hơn: git log --oneline
- git checkout (Id của thời điểm đã lưu).
  VD: git checkout c4759fd
- git checkout master để quay về thời điểm hiện tại.

# git branch

- xem tên của các thành viên trong dự án.
  <<<<<<< HEAD
- git checkout -b {branch name}.(câu lệnh để trỏ đến tên thành viên).

=======

- git branch -d (tên role) => để xóa 1 role.
- git checkout -b {branch name}.(câu lệnh để gán tên thành viên). VD: git checkout -b dev thì dev sẽ đc trở thành tên 1 thành viên
- git checkout (tên thành viên) để về lại với vai trò đó.
  VD: git checkout master thì sẽ về lại với role master.
  > > > > > > > dev

# git merge

- tổng hợp lại code về role chính.
  VD: git merge dev thì code ở role dev sẽ nhập vào role master.

<!-- Git Catalog -->
* [Thiết lập Git](#thiết-lập-git)
* [Commit](#commit)
* [Checkout](#checkout)
* [Branch](#branch)
* [GitHub](#github)
<!-- Git Catalog -->
## Thiết lập Git
- Thiết lập user name
```
git config --global user.name <user_name>
```
- Thiết lập mail
```
git config --global user.name <mail>
```
- Hiển thị danh sách thiết lập
```
git config --global --list
```
## Commit
- Tạo repository
```
git init
```
- Thêm file vào trong Index
```
git add <file_name>
```
- Thêm tất cả các file vào trong Index
```
git add --all
```
- Commit các file trong Index
```
git commit -m "<message>"
```
- Hiển thị trạng thái của tất cả các file
```
git status
```
- Hiển thị danh sách commit
```
git log
```
- Hiển thị chi tiết commit
```
git show <id_commit>
```
- Hiển thị thay đổi của các file đã được commit
```
git diff
```
## Checkout
- Xóa commit,thay đổi của các file commit sẽ ở Index
```
git reset --soft <id_commit>
```
- Xóa commit,thay đổi của các file commit sẽ ở Working tree
```
git reset --mixed <id_commit>
```
- Xóa commit và xóa thay đổi của các file commit
```
git reset --hard <id_commit>
```
## Branch
- Hiển thị danh sách của branch ở local
```
git branch
```
- Hiển thị danh sách của branch ở remote và local
```
git branch -a
```
- Tạo branch mới
```
git branch <branch_name>
```
- Tạo branch mới và checkout
```
git checkout -b <branch_name>
```
- Chuyển sang branch khác
```
git checkout <branch_name>
```
- Gộp branch hiện tại với branch khác
```
git merge <branch_name>
```
- Xóa branch
```
git branch -d <branch_name>
```
## GitHub
- Lấy repository từ GitHub
```
git clone <url>
```
- Lấy nội dung đã thay đổi từ repository ở GitHub
```
git pull
```
- Đưa nội dung đã thay đổi lên repository ở GitHub
```
git push
```
- Đưa nội dụng đã thay đổi của branch lên repository ở GitHub
```
git push origin <branch_name>
```
- Đưa nội dụng đã thay đổi và ghi đè lên các commit của branch lên repository ở GitHub
```
git push --force
```
- Xóa branch của repository trên GitHub
```
git push origin --delete <branch_name>
```

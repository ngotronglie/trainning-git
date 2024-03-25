# đây là phần đọc về git

đọc thêm tại [docs git](https://docs.github.com/fr/get-started/using-git/about-git)

- setup git 
- kiểm tra 
```cmd
git -v
git --version
```

- basic teminal command line

`cd ` di chuyển tới thư mục trong 

`cd ..` lui về 1 thư mục

`dir` hiển thị hết danh sách các tệp tin trong thư mục

`clear` dọn dẹp sạch teminal

`ls` hiển thị hết danh sách các tệp tin trong thư mục

`mkdir "folder name"`: tạo ra 1 thư mục mới tên "folder name"

bấm mũi tên lên để lấy lệnh cũ 

`touch "file name"`: tạo 1 file mới tên "file name" - có dấu kép thì nó không tạo file không mong muốn

`echo "name"`: in ra nội dung name


`echo "tieu de" > "file name"`:in vào file đó về tiêu đề cùa nhập (ghi đè)
`echo "tieu de" > "file name"`:in vào file đó về tiêu đề cùa nhập (không bị xóa chữ cũ)

`cat "file name"` hiển thị nội dung

`diff file1 file2`: so sánh khác nhau giữa 2 file

`rm file`: xóa file 

`rm -r "name folder"`: xóa folder có data

`rm -d "name folder"`: xóa folder rỗng

# english

- repository (repo): kho lưu trư
- commit (commit): cam ket - 1 don vi lam viec 
- branch (branch): nhanh
- main/master (master): ten repo chinh 
- merge/ rebase : ket hop 2 nhanh 
- develop: ten cua nhanh lap trinh vien


# git commands

`git --help`: help 

`git --version`: version show

`git status`: hien thi trang thai kho luu tru

`git init`: khoi tao 1 repo trong

`git log`: hien thi lich su commit

`git clone 'link'`: keo repo tu github ve

`git config -l`: xem cau hinh hien tai

`git config -l [--scope] [option_name] [value]`: 

**scope**
  -  -- system: tat ca nguoi dung
  -  -- global: lien quan toi repo(s)
  -  -- local: lien quan den 1 repo 


```
git config -l --global     :  thong tin nguoi co trong repo
git config -l --local      : 

```



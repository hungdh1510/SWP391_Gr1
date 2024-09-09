# SWP391_Gr1
Lần đầu lấy project:

Bước 1 ae tải Git về:

vào folder mà ae muốn lưu chuột phải git bash here
gõ câu lệnh git clone https://github.com/Nomap9/Mock_Project_03.git (tên tạo folder)
Bước 2 mở project tại nhánh của mình và liên kết với nhánh đã có trên Git (nhánh của ae mình đã tạo sẵn để tên ae): Vidu tôi clone project về rồi làm như sau:

git checkout -b Minh (tao và chuyển nhánh trên máy)
git push --set-upstream origin Minh (liên kết với nhánh cùng tên trên git, ae nhớ để trùng tên) *( Nếu push bị reject thì add git push -f origin tên nhánh trước )
Về sau mỗi khi chạy project ae pull code về từ nhánh main như sau:

Bước 1 đứng từ nhánh của mình gõ câu lệnh:

git pull (lấy code từ nhánh về, trường hợp ae trong nhóm sửa code của nhánh mình)
git merge main (lấy code từ nhánh chính main, thường không cần
Bước 2 khi code xong up code lên nhánh mình:

git add .
git commit -m "comment"
git push
Dưới đây là 1 số câu lệnh thường dùng:

git init

git add . >< git reset HEAD -- .

git commit -m "commit in here"

git status (kiem tra)

git diff index.html (xem trong file da sua dong nao) an q la ao

git branch (kiem tra cac nhanh, ke ca cac nhanh code cu)

git branch -a (kiem tra tat ca cac nhanh)

git branch -c ten nhanh (tao nhanh)

git checkout -b ten nhanh (tao nhanh xong chuyen sang nhanh moi)

git checkout ten nhanh (chuyen nhanh)

git branch -d ten nhanh (xoa nhanh, nhung khong duoc dung o nhanh dang xoa)

git branch -D ten nhanh (xoa khong ma can push code len)

git push -u origin ten nhanh/ git push origin -u ten nhanh (tao nhanh tren git)

git log (xem lich su commit)

git log --oneline (xem lich su commit de hon)

git checkout ma commit (ve lai code cu)

git merge ten nhanh (lay code tu nhanh khac ve nhanh hien tai)

git remote add link git ()

git push --set-upstream origin ten nhanh tren git (push code ve roi ket noi nhanh ten git)

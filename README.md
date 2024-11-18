# training-fe-2024
## Quy tắc đặt tên nhánh, commit trên Git
### Dev trên local máy tính cá nhân

- Pull code từ branch ‘master’ trước khi tạo branch mới
- Tạo branch mới theo quy tắc {type}/{subject}
    - type có thể là: build|ci|chore|docs|feat|fix|perf|refactor|revert|style|test
    - subject là tóm tắt nội dung chính của task
- Branch name tối đa 100 ký tự, sử dụng cú pháp snake-case loại 2 chữ thường
    
    VD: git checkout -b feat/html-css-template1
    

### Push code lên git

- Chỉ push code lên các nhánh đã tách ra từ nhánh master (trong project này)
- Nội dung commit push code lên cần tuân thủ quy tắc type(scope?):subject
    - type có thể là: build|ci|chore|docs|feat|fix|perf|refactor|revert|style|test
    - subject là tóm tắt nội dung chính của lần sửa đổi
- Nội dung commit phải viết bằng tiếng anh
- Nội dung commit không viết chung chung, không viết những câu vô nghĩa mà cần cô đọng ý chính của những phần code đã push lên
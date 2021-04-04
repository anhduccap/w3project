Làm quen với việc xây dừng web dựa trên dự án mẫu

    B1: Phân tích
    B2: Dựng base
    B3: Xây dựng từng thành phần theo phân tích
    B4: Hoàn thiện

    Các thành phần cơ bản của trang web
        + Header
        + Navigation (có thể ở chung với header)
        + Breadcrumb (Trang chủ > Khóa học > HTML + CSS,...)
        + Sidebar
        + Slider
        + Content
        + Footer

    Source: https://www.w3schools.com/w3css/tryw3css_templates_band.htm
    B1
        + Header, navigation
        + Slider
        + Content
            - About
            - Tour
            - Contact
            - Image
        + Footer

    B2: Tạo cấu trúc thư mục

    !!! Chuyển nhanh cấu trúc file html sang css
            - Bôi đen phần :    id="
            - Shift + Ctrl + L : Chọn tất cả các thành phần tương tự
            - Shift + Ctrl + ->  : Chọn tất cả tên ID
            - Coppy + Paste sang file CSS
            - Giữ Alt + click trước các id để thêm cursor để thêm #, và sau cursor (Ctrl + ->) để thêm {}
          
- Lỗi: failed to push some refs to: pull trước khi push để đồng bộ từ 2 phía
- Cách giải quyết cuối cùng là reset:
    + git reset --mixed origin/main
    + git add .
    + git commit -m "This is a new commit for what I originally planned to be amended"
    + git push origin main

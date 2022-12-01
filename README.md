# my_wedding_template
# Template cho thiệp cưới online

## Thiết kế
9 phần chính:
- **Header**: Mô tả những thông tin ngắn gọn về tên cô dâu, chú rể cũng như ngày tổ chức
- **About Us**: Mô tả những thông tin chi tiết về cô dâu chú rể
- **Countdown**: Đếm ngược đến ngày diễn ra lễ cưới
- **Events**: Thiệp mời và những sự kiện sẽ diễn ra
- **Story**: Mô tả về hành trình yêu với những cột mốc chính
- **Gallery**: Album ảnh
- **Attending**: Lời mời (again), nhưng thành khẩn hơn
- **Thanks**: Lời cảm ơn

## Hướng dẫn chỉnh sửa

### 1. Chỉnh sửa header: 
- Chữ: 
```
File "index.html", dòng 89-94: chỉnh sửa lại các thông tin của bản thân
```
- Ảnh:
```
Thay ảnh trong "images/background/header.jpg" thành ảnh của bản thân, ảnh này sẽ đóng vai trò như ảnh bìa, vẫn giữ tên là "header.jpg"
```

### 2. Chỉnh sửa About-us:
- Chữ:
```
File "index.html", 
dòng 116-119 => chỉnh sửa thông tin liên quan đến chú rể, dòng 128-130 => chỉnh sửa thông tin liên quan đến cô dâu
```
- Ảnh:
```
thay "images/avatar/groom.jpg" thành ảnh avatar của chú rể
thay "images/avatar/bride.jpg" thành ảnh avater của cô dâu
```

### 3. Chỉnh sửa CountDown
- Chữ:
```
File "index.html": Chỉnh dòng 143 thành thời gian tổ chức lễ cưới
File "wedding/js/main.js": Chỉnh dòng 284 thành thời gian tổ chức lễ cưới
```
- Ảnh:
```
Thay ảnh "images/background/countdown.jpg" thành ảnh mong muốn (nếu cần thiết)
```

### 4. Chỉnh sửa Events:
- Chữ:
```
File "index.html", dòng 190-263:
Chỉnh sửa lại các thông tin về thời gian cũng như địa điểm tổ chức các sự kiện
```
- Ảnh:
```
Thay ảnh trong folder "images/event/" thành ảnh mong muốn (nếu cần thiết)
```

### 5. Chỉnh sửa Story:
- Chữ: 
```
File "index.html", dòng 280-340:
Chỉnh sửa và bổ sung các thông tin về các mốc kỉ niệm đáng nhớ trong hành trình yêu
```
- Ảnh:
```
Thay ảnh trong folder "images/story/" thành ảnh mong muốn (giữ nguyên tên)
```

### 6. Chỉnh sửa Gallery
- Ảnh:
```
Thay ảnh trong folder "images/gallery/" thành ảnh mong muốn (giữ nguyên tên), ưu tiên một số ảnh nổi bật

Thay ảnh trong folder "images/album/" thành ảnh mong muốn (giữ nguyên tên), toàn bộ các ảnh muốn lưu trữ
```

Phần ảnh có nhiều customize, tự nghiên cứu thêm ở phần show ảnh trong 2 scripts ở cuối file `index.html` và `album.html`

### 7. Chỉnh sửa lời cảm ơn
- Chữ:
```
File "index.html", dòng 416, chỉnh sửa lại thông tin cô dâu, chú rể
```
- Ảnh:
```
Thay ảnh "images/background/bottom.jpg" thành ảnh mong muốn (nếu cần thiết)
```

## Hướng dẫn deploy lên github.io 
- [Các cách tạo web tĩnh với Github](https://techmaster.vn/posts/36510/cac-cach-tao-web-tinh-voi-github)
- [DNS domain về Github Page và thiết lập SSL free thông qua Cloudflare](https://chungtran4078.github.io/dns-domain-to-github-page-ssl-cloudflare/)


# Hướng dẫn sử dụng chương trình

Đây là hướng dẫn cơ bản về cách sử dụng chương trình của chúng tôi để tạo, tải lên và tải xuống file torrent.

## Cài đặt môi trường ảo Python

Đầu tiên, bạn cần tạo một môi trường ảo Python để cài đặt và quản lý các gói phụ thuộc của chương trình. Bạn có thể làm điều này bằng lệnh sau:

```
python3 -m venv myenv
```

Sau đó, bạn cần kích hoạt môi trường ảo bằng lệnh:

```
source myenv/bin/activate
```

## Chạy chương trình

1. Di chuyển đến thư mục chứa mã nguồn của chương trình:

```
cd app
```

2. Chạy tracker bằng lệnh:

```
python3 tracker2.py
```

3. Chạy peer bằng lệnh:

```
python3 peer2.py
```

## Cách truy cập

Tracker url: nhập http://<địa chỉ ip và port của tracker>
Địa chỉ ip và port sẽ hiện trên terminal của tracker2.py sau khi chạy file
VD: http://192.168.1.48:8080

### Tạo file torrent:

Để tạo file torrent, bạn làm theo các bước sau:

1. Nhấp vào nút Create Torrent trên giao diện chính
2. Sau khi xuất hiện cửa sổ giao diện tạo file torrent, click nút Choose file để chọn file cần tạo torrent
3. Nhấn chọn Create Torrent để tạo file
   File torrent sau khi tạo sẽ lưu ở trong cùng đường dẫn với file gốc

###  Upload file torrent:

Để upload file torrent, bạn làm các bước sau:
1. Nhấn chọn nút Upload File trên giao diện chính
2. Chọn file torrent cần tải lên (chỉ tải lên được định dạng torrent thôi, chọn file có định dạng khác sẽ báo lỗi)
3. Sau khi chọn file thì hệ thống sẽ tự động tải file torrent qua server

### Download file torrent:

Để download file torrent, bạn làm theo các bước sau:

1. Nhấn chọn Refresh để tải lại danh sách những file torrent mới nhất được upload lên server
2. Nhấp chọn file torrent cần tải, sau đó nhấn Download File (có thể giữ Ctrl khi chọn file để download được nhiều file cùng lúc)
3. Chọn nơi lưu file tải về, sau đó file sẽ được tải xuống

Vui lòng thay thế các thông tin cụ thể như đường dẫn và địa chỉ http theo yêu cầu của bạn.

Chúc bạn sử dụng chương trình thành công!

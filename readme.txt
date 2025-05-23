Dạ chào Thầy ạ.

Thư mục của em bao gồm: file ppt, báo cáo word, thư mục dự án.
Trong thư mục dự án được tổ chức như sau:

- link_dataset.txt : chứa đường dẫn đến dataset
- data: chứa data chưa xử lý và data đã xử lý (đã xóa đi data là ảnh)
- models: chứa các model đã train gồm 2 phần là one vs all và mô hình cnn
- notebooks: chứa các notebook nghiên cứu gồm:
+ get_dataset
+ test_model
+ train_cnn
+ train cnn + svm( xử lý ảnh theo phương pháp HOG)
- reports: chứa các kết quả biểu dồ loss, accuracy và bảng classification report
- requirement.txt dùng để tải các thư viện dùng cho dự án

***file train_cnn sẽ không có kết quả run do lúc huấn luyện trên kaggle không lưu trữ nổi train trong 1 lượt, nên em phải chạy 4 lần do đó không có kết quả ạ***
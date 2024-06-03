# Chương Trình Tính Toán Và Phân Tích Điểm Thi

## Tổng Quan

Dự án này nhằm mục đích giảm bớt thời gian chấm điểm cho các lớp học đông học sinh, có thể lên đến hàng nghìn học sinh. Chương trình sẽ đọc các bài làm từ các tệp văn bản bên ngoài, kiểm tra tính hợp lệ của dữ liệu, chấm điểm từng bài thi theo đáp án được cung cấp và tạo báo cáo chi tiết. Điều này giúp giáo viên tiết kiệm thời gian và có cái nhìn sâu sắc hơn về hiệu quả học tập của học sinh.

## Tính Năng

1. **Xử Lý Tệp Tin Với Quản Lý Ngoại Lệ**: Mở và đọc tệp văn bản một cách an toàn, xử lý trường hợp tệp không tồn tại.
2. **Kiểm Tra Dữ Liệu**: Phân tích từng dòng dữ liệu bài làm để xác định tính hợp lệ và báo cáo các lỗi nếu có.
3. **Chấm Điểm**: Chấm điểm từng bài thi dựa trên đáp án chuẩn, tính đến các câu trả lời đúng, sai và bỏ trống.
4. **Báo Cáo**: Tạo các báo cáo chi tiết, bao gồm:
    - Tổng số dòng dữ liệu hợp lệ và không hợp lệ
    - Điểm của từng học sinh
    - Thống kê tổng quan (điểm cao nhất, thấp nhất, trung bình, và trung vị)
    - Các câu hỏi bị bỏ qua nhiều nhất hoặc trả lời sai nhiều nhất
5. **Xuất File**: Lưu kết quả chấm điểm vào các tệp CSV và văn bản có tên phù hợp để phân tích và lưu trữ.

## Yêu Cầu

- Python 3.x
- Pandas
- NumPy

## Cài Đặt

Đảm bảo bạn đã cài đặt Python 3 và các thư viện cần thiết. Bạn có thể cài đặt các thư viện cần thiết bằng pip:

```bash
pip install pandas numpy

Sử Dụng
1. Đặt Các Tệp Dữ Liệu
Lưu các tệp văn bản chứa bài làm của học sinh vào một thư mục chỉ định trên máy tính của bạn. Đảm bảo rằng mỗi tệp có tên phù hợp với lớp học, ví dụ: class1.txt, class2.txt.

2. Chạy Chương Trình
Thực thi script và nhập tên lớp khi được yêu cầu. Đảm bảo rằng tệp grade_calculator.py nằm cùng thư mục với các tệp dữ liệu.

bash
Sao chép mã
python grade_calculator.py
3. Nhập Tên Lớp
Khi được yêu cầu, nhập tên tệp lớp (ví dụ: class1 cho tệp class1.txt).

Ví dụ:

bash
Sao chép mã
Enter a class name to grade (i.e. class1 for class1.txt): class1
Chương trình sẽ xử lý tệp class1.txt, kiểm tra dữ liệu, chấm điểm từng bài thi, và tạo báo cáo.

Kết Quả
Chương trình sẽ tạo ra các file kết quả sau:

class1_grades.csv: File CSV chứa điểm của từng học sinh.
class1_grades.txt: File văn bản chứa điểm của từng học sinh.
Báo cáo chi tiết về các câu hỏi bị bỏ qua nhiều nhất hoặc trả lời sai nhiều nhất.
Đóng Góp
Nếu bạn muốn đóng góp cho dự án, vui lòng tạo pull request hoặc báo lỗi tại repository trên GitHub.

Giấy Phép
Dự án này sử dụng giấy phép MIT. Xem file LICENSE để biết thêm chi tiết.

markdown
Sao chép mã

4. **Lưu file**: Nhấn `Ctrl+S` để lưu file.

### Đẩy code và file `README.md` lên GitHub

1. **Khởi tạo repository git trong thư mục dự án**:
    - Mở Terminal hoặc Command Prompt và chuyển đến thư mục dự án của bạn.

```bash
git init
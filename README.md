# Website Quiz

Chào mừng bạn đến với dự án **Website Quiz**! Đây là một ứng dụng quiz trực tuyến đơn giản cho phép người dùng tham gia trả lời các câu hỏi và xem kết quả đúng hay sai sau khi hoàn thành bài kiểm tra. Hệ thống này có giao diện thân thiện và dễ sử dụng, phù hợp cho việc kiểm tra kiến thức của người dùng.

## Mô tả hệ thống

Ứng dụng **Website Quiz** cung cấp một nền tảng quiz trực tuyến cho phép người dùng tham gia vào các câu hỏi trắc nghiệm. Sau khi người dùng hoàn thành quiz, hệ thống sẽ hiển thị kết quả cho họ, bao gồm các câu trả lời đúng và sai.

### Các tính năng chính:
- **Trả lời câu hỏi**: Người dùng có thể trả lời các câu hỏi trắc nghiệm với nhiều lựa chọn đáp án. 
- **Xem kết quả ngay lập tức**: Sau khi hoàn thành quiz, người dùng có thể xem lại các câu trả lời của mình và biết câu nào đúng, câu nào sai.
- **Giao diện thân thiện**: Ứng dụng có giao diện người dùng đơn giản, dễ sử dụng, và dễ dàng tương tác.

## Cài đặt

Để cài đặt và chạy dự án này trên máy tính của bạn, vui lòng làm theo các bước dưới đây. Hướng dẫn này sẽ giúp bạn clone dự án, cài đặt các thư viện phụ thuộc và khởi động ứng dụng trên máy tính của bạn.

### Yêu cầu hệ thống:
- **Node.js**: Phiên bản 12 hoặc cao hơn. Bạn có thể tải và cài đặt Node.js từ [https://nodejs.org/](https://nodejs.org/).
- **NPM** (hoặc **Yarn**): Đây là các công cụ để quản lý các thư viện phụ thuộc trong dự án.

### Các bước cài đặt chi tiết:

1. **Clone repository**:
   Đầu tiên, clone repository này về máy tính của bạn bằng cách sử dụng lệnh Git dưới đây. Lệnh này sẽ tải tất cả mã nguồn của dự án từ GitHub về máy tính.

   ```bash
   git clone https://github.com/ledinhnhat1102/Website_Quiz.git
Di chuyển vào thư mục dự án: Sau khi clone xong, di chuyển vào thư mục của dự án:

bash
Copy code
cd Website_Quiz
Cài đặt các thư viện phụ thuộc: Sau khi vào thư mục dự án, bạn cần cài đặt các thư viện phụ thuộc mà dự án yêu cầu. Bạn có thể sử dụng npm hoặc Yarn.

Cài đặt với npm:
bash
Copy code
npm install
Cài đặt với Yarn:
bash
Copy code
yarn install
Lệnh này sẽ tự động cài đặt tất cả các thư viện cần thiết cho dự án, được liệt kê trong file package.json.

Cấu hình cơ sở dữ liệu:

Hệ thống yêu cầu cơ sở dữ liệu để lưu trữ câu hỏi và kết quả người dùng. Bạn có thể sử dụng MySQL, MongoDB, hoặc một cơ sở dữ liệu khác.
Cập nhật thông tin kết nối cơ sở dữ liệu trong các file cấu hình (ví dụ: config/database.js hoặc config.js), tùy thuộc vào cách bạn cấu hình dự án.
Ví dụ: Nếu bạn sử dụng MySQL, bạn sẽ cần cấu hình thông tin đăng nhập như sau:

js
Copy code
const dbConfig = {
  host: 'localhost',
  user: 'root',
  password: 'your_password',
  database: 'quiz_db'
};
Chạy ứng dụng: Sau khi cài đặt xong và cấu hình cơ sở dữ liệu, bạn có thể khởi động ứng dụng bằng lệnh sau:

Với npm:
bash
Copy code
npm start
Với Yarn:
bash
Copy code
yarn start
Ứng dụng sẽ chạy trên địa chỉ http://localhost:3000. Bạn có thể thay đổi cổng nếu cần trong file cấu hình.

Truy cập vào ứng dụng: Sau khi ứng dụng đã được khởi động, mở trình duyệt web và truy cập vào địa chỉ sau:

arduino
Copy code
http://localhost:3000
Tại đây, bạn sẽ thấy giao diện quiz. Người dùng có thể bắt đầu trả lời câu hỏi ngay lập tức.

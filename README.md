# Khoa_luan_tot_nghiep
Đề tài: 

- Tên tiếng Việt: Đánh giá hiệu quả của các phương pháp phát hiện và giải nén tập tin thực thi bị đóng gói trong phát hiện mã độc Windows.
- Tên tiếng Anh: Evaluating the effectiveness of detecting and unpacking methods for packed executable files in Windows malware detection. 

Tóm tắt đề tài:

- Trong khóa luận này, nhóm chúng tôi sẽ tập trung nghiên cứu các công cụ phát hiện và giải nén các tập tin thực thi Windows khi các tập tin này bị đóng gói để ngăn chặn việc phân tích ngược và che giấu hành vi bất thường.
- Trong phạm vi của Khóa luận tốt nghiệp, chúng tôi sẽ tập trung nghiên cứu cấu trúc của các tập tin thực thi Windows (Portable Executable- PE), bao gồm các thành phần chính và cách chúng hoạt động. Bên cạnh đó, nhóm sẽ tìm hiểu các trình đóng gói phổ biến hiện nay trên thị trường, cơ chế hoạt động của chúng, cách chúng tác động đến các tệp tin PE, từ đó phân tích cách các trình đóng gói này bảo vệ mã nguồn và che giấu dữ liệu. Để phục vụ quá trình nghiên cứu, nhóm sử dụng bốn công cụ chính: Unipacker, ClamAV, PeiD và Detect It Easy (DIE). Đây đều là những công cụ phổ biến trong việc nhận diện và phân loại các trình đóng gói (packer). Hai trong số bốn công cụ trên còn có khả năng giải nén, giúp truy xuất mã gốc nhanh chóng và hiệu quả. Chúng tôi sẽ đánh giá hiệu quả của từng công cụ trong việc phát hiện và giải nén, sau đó đưa ra sự so sánh và nhận xét về các công cụ này.
- Cuối cùng, sau khi thực hiện quá trình giải nén, các mẫu đã được xử lý sẽ được sử dụng làm đầu vào cho các mô hình học máy hiện hành nhằm đánh giá hiệu quả phát hiện mã độc. Nhờ đó không chỉ giúp kiểm chứng chất lượng đầu ra của các công cụ giải nén, mà còn góp phần đánh giá mức độ ảnh hưởng của các kỹ thuật đóng gói đến độ chính xác của mô hình phát hiện.

# Phân tích khám phá dữ liệu về bệnh Đái tháo đường

## Giới thiệu
- Phân tích khám phá dữ liệu (Exploratory Data Analysis - EDA) là quá trình quan trọng đầu tiên trong bất kỳ dự án khoa học dữ liệu nào, đặc biệt là trong lĩnh vực y tế như nghiên cứu về bệnh đái tháo đường. 
- EDA là phương pháp tiếp cận hệ thống nhằm phân tích, tóm tắt và trực quan hóa dữ liệu để hiểu rõ hơn về đặc điểm, mô hình và xu hướng tiềm ẩn trong tập dữ liệu.

## Mục đích
- Trong bối cảnh nghiên cứu về bệnh đái tháo đường, EDA giúp chúng ta khám phá các mối quan hệ phức tạp giữa các yếu tố nguy cơ, triệu chứng lâm sàng, và kết quả chẩn đoán. 
- Quá trình này không chỉ giúp làm sạch và chuẩn bị dữ liệu mà còn cung cấp những hiểu biết sâu sắc về bản chất của bệnh lý, từ đó định hướng cho các bước phân tích tiếp theo. 

## [Báo cáo về các loại nguyên nhân Và khái niệm cơ bản của ADAP](/baitapnhom/Lab3/docs)
- [Mô tả các loại nguyên nhân: ](/baitapnhom/Lab3/docs/Chuong7.docx) 
    + Đái tháo đường Típ 1 (phá hủy tế bào beta, thường dẫn đến thiếu hụt insulin tuyệt đối)
    + Đái tháo đường Vô căn
    + Loại 2 (chủ yếu là kháng insulin kèm thiếu hụt insulin tương đối hoặc chủ yếu là khiếm khuyết tiết insulin kèm/không kèm kháng insulin)

- [Sử dụng thuật toán học ADAP để dự đoán sự khởi phát của bệnh tiểu đường: ](/baitapnhom/Lab3/docs/KhaiNiemCoBanCuaADAP.docx)
Nghiên cứu này sử dụng thuật toán mạng nơ-ron **ADAP** để dự báo khả năng mắc bệnh tiểu đường trong vòng 5 năm ở nhóm dân số người da đỏ Pima - một cộng đồng có tỷ lệ tiểu đường rất cao tại Arizona, Mỹ.
Kết quả chính: Thuật toán đạt độ chính xác 76% trong cả độ nhạy (khả năng phát hiện người sẽ mắc bệnh) và độ đặc hiệu (khả năng xác định người không mắc bệnh).

## [Code phân tích khám phá dữ liệu: ](/baitapnhom/Lab3/code/)
- Mô tả vấn đề: Bệnh tiểu đường là một trong những bệnh mạn tính phổ biến và nguy hiểm, đặc biệt trong nhóm người có yếu tố nguy cơ như béo phì, tuổi cao, hoặc có tiền sử gia đình.  
Bộ dữ liệu **Pima Indians Diabetes** được thu thập từ phụ nữ Pima (Arizona, Mỹ) ≥ 21 tuổi, nhằm mục tiêu phân tích các yếu tố sức khỏe liên quan đến khả năng mắc bệnh tiểu đường.  
- Import thư viện và nạp dữ liệu
- Chuẩn bị dữ liệu (Prepare Data)
- Phân tích dữ liệu (Analyze Data):
    + Thống kê mô tả
    + Trực quan hóa dữ liệu
    + Trực quan hóa mối quan hệ giữa các thuộc tính
    + Thuật toán học ADAP để dự đoán sự khởi phát của bệnh đái tháo đường
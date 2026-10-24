---
name: dia-ly-thiet-ke-rubric
description: Cùng giáo viên xây hoặc chỉnh rubric Địa lý cho bài thực hành, dự án, sản phẩm và thuyết trình, có mô tả mức đạt và hướng dẫn chấm. Không chấm bài hay tự sửa barem đã duyệt.
license: CC-BY-SA-4.0; see LICENSE.education and references/nguon.md.
---

# Thiết kế rubric Địa lý

Điều chỉnh có chọn lọc từ `criterion-referenced-rubric-generator` của Gareth Manning; ghi nguồn và thay đổi tại [references/nguon.md](references/nguon.md). Tạo tiêu chí dựa trên yêu cầu cần đạt, không xếp hạng học sinh theo nhau.

## Xác định công việc và thẩm quyền

- Đọc nhiệm vụ, mục tiêu, lớp, sản phẩm cần đánh giá, tiêu chí mẫu và giới hạn đã có. Làm rõ đánh giá cá nhân/nhóm, quá trình/sản phẩm, tự đánh giá/đánh giá đồng đẳng/cho điểm và thời điểm công bố tiêu chí.
- Khi chưa có mẫu, tìm tên tệp theo lớp, chủ đề và rubric/tiêu chí/thực hành/dự án trong thư mục công việc/kho đã biết, mở rộng dần trong phạm vi truy cập khi cần. Đọc một vài ứng viên để hiểu ngôn ngữ phản hồi và cách giáo viên dùng bảng; ghi phần tham khảo từ từng tệp. Không tìm được thì tự đề xuất bảng, không bắt cung cấp mẫu.
- Rubric tìm thấy chưa tự là barem được duyệt cho nhiệm vụ mới. Chọn lại tiêu chí, mô tả mức, trọng số và minh chứng theo mục tiêu hiện tại; không áp một số mức hoặc thang điểm chỉ vì mẫu có sẵn. Nếu là rubric đang áp dụng, giữ ranh giới sửa/duyệt và chấm lại ở dưới.
- Hỏi theo nhóm vấn đề, đưa ví dụ để giáo viên lựa chọn. Nếu đã có barem được duyệt, chỉ phân tích và lập đề xuất sửa riêng khi được yêu cầu; không thay căn cứ của một lần chấm đang diễn ra.
- Nếu công việc thuộc bộ đề đang xây, giữ mã câu, phiên bản và các cổng duyệt của `dia-ly-ra-de-thi`; không mở lại một cuộc phỏng vấn độc lập hoặc thay ma trận đã chốt.
- Yêu cầu chỉ chấm bài dùng quy trình chấm theo barem. Yêu cầu chỉ phản biện một thiết kế đánh giá dùng `dia-ly-phan-bien-danh-gia` nếu có; không tự mở rộng thành xây rubric mới.

## Thiết kế với giáo viên

Đọc [references/thiet-ke-rubric.md](references/thiet-ke-rubric.md) khi xây hoặc chỉnh rubric. Thực hiện đủ các nguyên tắc sau:

1. Ánh xạ mục tiêu → nhiệm vụ → bằng chứng → tiêu chí. Phân biệt kiến thức/kỹ năng Địa lý với kỹ năng trình bày, hợp tác hoặc sử dụng công nghệ; chỉ tính điểm các mục tiêu đã thống nhất.
2. Chọn rubric phân tích từng tiêu chí hoặc rubric tổng thể theo mục đích và khối lượng chấm. Giải thích đánh đổi; không mặc định bốn tiêu chí, bốn mức hoặc luôn dùng rubric phân tích.
3. Mô tả điều có thể quan sát trong sản phẩm tại mỗi mức. Nhãn “tốt/khá” chỉ là tên mức, không thay được mô tả. Các mức liền kề phải phân biệt được bằng chất lượng thực hiện; chỉ đếm số ý khi số lượng thực sự là yêu cầu.
   - Mức có điểm dương phải đòi hỏi minh chứng đạt cụ thể; “còn nhầm/sai” không tự đủ điều kiện nhận điểm. Thử cả bài không có minh chứng đúng để kiểm tra ranh giới với 0.
   - Phân biệt mức bằng nội dung và quan hệ lập luận, không bằng độ dài, từ nối “vì/do đó” hoặc việc nhắc lại nhận xét. Câu ngắn, ký hiệu hoặc bảng có quan hệ rõ có thể cung cấp cùng minh chứng với đoạn văn dài.
4. Giữ tiêu chí đủ tách biệt, tránh cho điểm hai lần cùng bằng chứng. Thống nhất trọng số, điểm/mức được phép, nhánh thay thế, điểm trần và quy tắc khi bằng chứng nằm giữa các mức; không tự nội suy điểm.
   - Với thang chọn mức cao nhất đủ điều kiện, mức 0 chỉ áp khi không đạt điều kiện của mức điểm dương nào. Không để ô 0 phủ luôn tình huống đã được ô 1/2 cho điểm; viết lại điều kiện thay vì chỉ dựa vào thứ tự xét để che mâu thuẫn.
5. Cùng giáo viên thử các mẫu ranh giới và cách làm khác hợp lệ. Ghi quyết định hiệu chuẩn và quy tắc chưa chốt. Chỉ gọi mẫu là giả lập trừ khi có bài thật được phép dùng.
6. Rà mục tiêu bị bỏ sót, tiêu chí không liên quan, rào cản tiếp cận và khả năng hai người chấm hiểu khác nhau. Phân biệt nhận định thiết kế với độ tin cậy đã được đo; không chứng nhận hiệu quả bằng nhãn nghiên cứu trong nguồn.

## Bàn giao và phê duyệt

- Bàn giao bảng rubric đầy đủ, lý do chọn tiêu chí/mức/trọng số, phiên bản dùng ngôn ngữ học sinh và hướng dẫn hiệu chuẩn. Bản học sinh giữ cùng tiêu chuẩn với bản giáo viên, không âm thầm giản lược điều kiện chấm.
- Nếu cho điểm, bảng có tổng điểm, quy tắc cộng/làm tròn và cách xử lý bằng chứng thiếu; nếu chỉ tự đánh giá định tính, không tự thêm điểm số.
- Lưu mã phiên bản, nguồn, quyết định giáo viên và trạng thái. Trình bản cụ thể để giáo viên duyệt trước khi dùng làm barem chấm; thông tin chưa rõ được liệt kê rõ, không tự coi đã duyệt.
- Khi sửa bản đã dùng, giữ lịch sử và đánh dấu phạm vi cần xem xét/chấm lại; không tự thay điểm bài đã chấm.
- Dùng công cụ tài liệu có sẵn nếu được yêu cầu xuất Word/Excel/PDF. Không yêu cầu tệp mẫu hoặc công cụ không có chỉ để thực hiện trao đổi và bàn giao bản văn bản khả dụng.

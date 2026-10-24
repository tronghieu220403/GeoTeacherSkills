# GeoTeacherSkills

Sáu skill dành cho giáo viên Địa lý Việt Nam:

- [dia-ly-giao-an](skills/dia-ly-giao-an/SKILL.md): giáo án, phiếu học tập, tiêu chí đánh giá và dự kiến lỗi; có chế độ cùng giáo viên chuẩn bị lên lớp khi được yêu cầu.
- [dia-ly-bai-giang](skills/dia-ly-bai-giang/SKILL.md): PowerPoint, ghi chú có lỗi dự kiến/câu hỏi hỗ trợ, tiêu chí học sinh và chế độ tập triển khai theo slide khi được yêu cầu.
- [dia-ly-ra-de-thi](skills/dia-ly-ra-de-thi/SKILL.md): thảo luận kỹ yêu cầu, thống nhất ma trận, xây dựng và duyệt đề, đáp án, barem.
- [dia-ly-cham-bai-theo-barem](skills/dia-ly-cham-bai-theo-barem/SKILL.md): chấm theo barem đã được giáo viên duyệt, truy vết từng khoản điểm và chuyển trường hợp chưa rõ để giáo viên quyết định.
- [dia-ly-thiet-ke-rubric](skills/dia-ly-thiet-ke-rubric/SKILL.md): thiết kế bảng tiêu chí với mức mô tả quan sát được, bản học sinh và hướng dẫn hiệu chuẩn.
- [dia-ly-phan-bien-danh-gia](skills/dia-ly-phan-bien-danh-gia/SKILL.md): rà mục tiêu, nhiệm vụ, minh chứng, điểm và cách diễn giải kết quả; đề xuất sửa có căn cứ.

[AGENTS.md](AGENTS.md) chứa hướng dẫn chung và cách phối hợp sáu skill. Phần cốt lõi về rubric/phản biện được tích hợp trong quy trình hiện có; hướng dẫn chuyên sâu nằm trong hai skill riêng, chỉ đọc khi cần. Chấm bài không tự sửa barem vì phát hiện vấn đề thiết kế. Chế độ chuẩn bị lên lớp không tự bật sau mỗi lần tạo giáo án/PowerPoint.

Không cần biết trước khuôn mẫu: khi thiếu mẫu, Codex tìm tên tệp trong các thư mục công việc/tài liệu khả dụng, đọc một vài ứng viên phù hợp và có thể kết hợp cấu trúc, cách dạy, thiết kế hoặc bảng biểu từ nhiều tệp để phù hợp giáo viên. Mẫu cũ không tự quyết định kiến thức, quy định hay barem hiện tại; căn cứ chấm vẫn phải được giáo viên chỉ định. Không có mẫu phù hợp thì tự dựng bố cục và tiếp tục phần đủ căn cứ.

Mỗi thư mục trong `skills/` là một gói độc lập. Các tài liệu trong `references/` được dùng khi thực hiện quy trình tương ứng. Kho là bản nguồn; bản cài cá nhân là bản sao trong thư mục skill của Codex, cần được đồng bộ khi cập nhật. Không có đề thi, barem hoặc bài học sinh thực tế trong kho này.

Một số skill có liên kết tùy tình huống sang module của skill cùng bộ; cài cả sáu skill để dùng đủ các liên kết chuyên sâu. Các gói giữ nguyên tắc cốt lõi và thông tin nguồn cần thiết tại chỗ.

Nguồn kế thừa: Learning Commons (`k12-lesson-plan-creation`, `k12-lesson-prep`, Apache-2.0) và Gareth Manning / Education Agent Skills (`criterion-referenced-rubric-generator`, `assessment-validity-checker`, CC BY-SA 4.0). Các phần điều chỉnh được xác định và ghi công trong từng gói, kèm bản giấy phép tương ứng; không có một giấy phép chung mới áp lên toàn bộ kho.


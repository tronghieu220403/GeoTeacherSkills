# Nguồn kế thừa và điều chỉnh

Skill này là bản điều chỉnh có chọn lọc, không phải bản dịch toàn bộ hoặc bản phát hành chính thức của Learning Commons hay Anthropic.

- Kho nguồn: https://github.com/learning-commons-org/agent-skills
- Skill nguồn: `skills/k12-lesson-plan-creation/`.
- Commit đã đọc: `8b0599c244696d9a8e6978dd58a426f475f37c45`.
- Ngày điều chỉnh: 2026-10-24.
- Giấy phép phần kế thừa bài dạy ban đầu: Apache-2.0, giữ trong `../LICENSE`; ghi công ở `../NOTICE`. Các phần bổ sung đánh giá và chuẩn bị lên lớp được xác định riêng trong [nguon-bo-sung.md](nguon-bo-sung.md).

Các tài liệu nguồn đã dùng để điều chỉnh:

- [SKILL.md](https://github.com/learning-commons-org/agent-skills/blob/8b0599c244696d9a8e6978dd58a426f475f37c45/skills/k12-lesson-plan-creation/SKILL.md): xác định yêu cầu, soạn học liệu dùng được và cập nhật nhất quán giữa các sản phẩm.
- [references/social_studies.md](https://github.com/learning-commons-org/agent-skills/blob/8b0599c244696d9a8e6978dd58a426f475f37c45/skills/k12-lesson-plan-creation/references/social_studies.md): liên kết câu hỏi, nguồn, hoạt động và bằng chứng học tập.
- [references/output.md](https://github.com/learning-commons-org/agent-skills/blob/8b0599c244696d9a8e6978dd58a426f475f37c45/skills/k12-lesson-plan-creation/references/output.md): học liệu thực có, nhiệm vụ đồng bộ, thời gian gồm chuyển tiếp và khả năng sử dụng bản in.

Thay đổi trong bản này:

1. Viết lại hướng dẫn bằng tiếng Việt cho giáo viên Địa lý Việt Nam; thay nhánh nhiều môn bằng phạm vi môn/phân môn Địa lý.
2. Thay chuẩn theo bang Mỹ và yêu cầu khung C3 bằng căn cứ chương trình, tài liệu và mẫu trường thực sự được cung cấp hoặc xác minh. Không tự gán số hiệu văn bản Việt Nam.
3. Thay chuỗi câu hỏi cố định và bước xin phép tạo bản đầy đủ bằng việc hỏi phần làm thay đổi nội dung, hoặc duyệt khung khi giáo viên muốn thảo luận trước.
4. Bỏ phụ thuộc Claude Docs/Design, Bash renderer, schema JSON và Knowledge Graph; dùng skill xử lý tài liệu có sẵn trong môi trường Codex. Không yêu cầu cài dịch vụ bên ngoài.
5. Thay các sản phẩm bắt buộc của nguồn bằng sản phẩm thuộc phạm vi nhiệm vụ, thêm yêu cầu nguồn số liệu, bản đồ/Atlat, địa giới và ranh giới với ra đề/chấm bài.
6. Giữ nguyên tắc học liệu sẵn dùng, liên kết mục tiêu–nhiệm vụ–bằng chứng, phân hóa khi phù hợp và nội dung chung giữa các tài liệu. Không sao chép ví dụ bài học hoặc nhận định pháp lý về quyền sao chép từ nguồn.

Không cần đọc lại nguồn trực tuyến để chạy skill. Khi tiếp tục điều chỉnh phần kế thừa, giữ ghi công, giấy phép và dấu vết phiên bản; không ngụ ý tác giả nguồn đã duyệt bản tùy biến.

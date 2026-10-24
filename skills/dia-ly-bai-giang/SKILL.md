---
name: dia-ly-bai-giang
description: Tạo/chỉnh PowerPoint Địa lý, ghi chú giảng dạy; cùng giáo viên tập triển khai bài bằng slide khi được yêu cầu. Không dùng để ra đề thi hoặc chấm bài.
---

# Bài giảng PowerPoint Địa lý

Quy trình gốc viết mới cho GeoTeacherSkills, bổ sung phương pháp đánh giá từ Education Agent Skills và chuẩn bị lên lớp từ Learning Commons; xem [references/nguon-bo-sung.md](references/nguon-bo-sung.md). Phụ trách nội dung sư phạm và tính thống nhất của bài giảng; sử dụng skill Presentations có sẵn để tạo/chỉnh và kiểm tra tệp.

## 1. Đọc đầu vào và xác định loại công việc

- Xác định đang tạo mới, chuyển giáo án thành slide, sửa nội dung, cải thiện thiết kế hoặc tuân theo PowerPoint mẫu. Đọc tệp gốc và mẫu trước khi chọn cách làm.
- Lấy lớp, phân môn, chủ đề, bộ sách/tài liệu, mục tiêu, thời lượng và điều kiện trình chiếu từ ngữ cảnh. Chỉ hỏi phần quan trọng còn thiếu; không yêu cầu giáo viên khai lại dữ liệu đã có trong giáo án.
- Với bài tạo từ giáo án, dùng phiên bản giáo án được chỉ định làm căn cứ về mục tiêu, nội dung, hoạt động và số liệu. Nếu phát hiện sai hoặc mâu thuẫn, trình vấn đề và đề xuất; không âm thầm thay đổi kiến thức.
- Với yêu cầu chỉ có chủ đề, xác định mục tiêu và chuỗi hoạt động tối thiểu để xây bài trình chiếu; không mặc định phải tạo thêm một giáo án Word. Nếu cả hai sản phẩm được yêu cầu, phối hợp `dia-ly-giao-an` khi có.
- Theo mẫu, phông, tỷ lệ màn hình, số slide hoặc yêu cầu hình ảnh được chỉ định. Nếu chưa có định hướng thiết kế, theo quy trình lựa chọn mẫu của skill Presentations; không tự bỏ qua bước mà công cụ đó yêu cầu.
- Với “làm đẹp”, giữ nội dung và trình tự có ý nghĩa, kiểm tra các đối tượng, hình, biểu đồ, ghi chú và hiệu ứng liên quan; ghi rõ thay đổi nội dung được giáo viên đồng ý, nếu có.
- Nếu phần chữ phải giữ có lỗi chuyên môn, giữ bản nguồn và chỉ ra lỗi cùng bản sửa đề xuất. Bản vẫn chứa kết luận sai trên màn hình phải được bàn giao rõ là chưa sẵn sàng dùng; sửa trong ghi chú không làm kết luận trên slide thành đúng. Không tự chuyển lỗi thành “câu hỏi bẫy” khi chưa thống nhất mục đích.

## 2. Lập bản thiết kế bài giảng

- Dùng [references/ban-thiet-ke-slide.md](references/ban-thiet-ke-slide.md) để ghi mạch bài, hoạt động, dữ kiện dùng chung, vai trò hình ảnh và ghi chú. Đây là hồ sơ làm việc, không phải phần chữ đưa nguyên lên slide.
- Theo mạch giáo án hoặc mục tiêu đã thống nhất: khơi gợi vấn đề, khai thác kiến thức/học liệu, luyện tập, tổng hợp và vận dụng khi phù hợp. Không ép một số slide hoặc trình tự cố định cho mọi bài.
- Mỗi slide phục vụ một ý hoặc nhiệm vụ rõ; tiêu đề nói được nội dung cụ thể. Phân biệt slide giáo viên giải thích, học sinh quan sát, thảo luận, luyện tập và kiểm tra nhanh.
- Ước lượng thời gian theo hoạt động, gồm quan sát, suy nghĩ và phản hồi; nhiều slide có thể phục vụ một hoạt động. Không lấy số slide làm thời gian dạy hoặc đọc toàn bộ giáo án lên màn hình.
- Chọn mức chữ phù hợp học sinh và khoảng cách trình chiếu. Đưa phần giải thích dài, lời dẫn và gợi ý xử lý vào ghi chú giáo viên; slide vẫn đủ hướng dẫn để học sinh thực hiện.
- Nếu giáo viên muốn duyệt khung, trình mạch bài và vài slide đại diện cụ thể rồi tiếp thu trước khi tạo trọn bộ. Nếu yêu cầu đã rõ, thực hiện theo phạm vi đã được giao, không thêm cổng duyệt không cần thiết.

## 3. Hình ảnh, bản đồ, số liệu và hoạt động

- Ưu tiên hình, bản đồ, sơ đồ và biểu đồ thực sự giúp đạt mục tiêu. Mỗi hình chính có câu hỏi hoặc ý nghĩa giảng dạy; không thêm ảnh trang trí gây nhiễu hoặc che dữ kiện.
- Kiểm tra nguồn, phiên bản, năm, phạm vi và chú giải bản đồ/Atlat; không bịa số trang. Không cắt mất phần cần để đọc bản đồ hoặc dùng ảnh AI thay bản đồ địa lý chính xác.
- Với bảng và biểu đồ, giữ nguyên dữ liệu nguồn, đơn vị, trục, năm và chú giải. Tính lại đáp án, đối chiếu số trên slide và ghi chú. Dùng bảng/biểu đồ có thể chỉnh sửa khi công cụ hỗ trợ; ảnh nguồn được dùng trung thực, không giả rằng có thể chỉnh từng dữ liệu.
- Giữ tên địa danh và phạm vi lãnh thổ phù hợp mốc dữ liệu và tài liệu giáo viên chọn; nêu khác biệt cần làm rõ thay vì trộn các phiên bản địa giới.
- Dùng nguồn được phép sử dụng và ghi công phù hợp; không giả URL, trích dẫn hoặc giấy phép. Trích nguồn ngắn cạnh học liệu và có danh mục nguồn khi cần; ghi rõ số liệu giả định nếu được dùng.
- Nhiệm vụ học sinh nêu rõ dữ kiện, câu hỏi, cách trả lời và thời gian khi cần. Ghi đáp án, gợi ý và cách xử lý sai lầm trong ghi chú hoặc slide đáp án riêng theo cách giáo viên chọn.
- Tự làm nhiệm vụ trọng tâm từ dữ kiện/hình thật; trong ghi chú các hoạt động dễ nhầm, ghi câu trả lời gần đúng giả lập, dấu hiệu nhận ra lỗi, câu hỏi gợi mở và bước hỗ trợ tiếp theo. Không coi dự đoán là quan sát học sinh thực tế hoặc hiện sẵn đáp án lên màn hình khi học sinh chưa thực hiện nhiệm vụ.
- Với nhiệm vụ có đánh giá, hiển thị tiêu chí quan sát hoặc bản rubric học sinh đã thống nhất ở thời điểm phù hợp; tiêu chí và mức phải giữ đúng bản giáo viên. Không tự tăng/giảm trọng số, tạo barem mới hoặc tiết lộ rubric kỳ thi chưa công bố.
- Kiểm tra câu hỏi/hoạt động có đo mục tiêu, đủ dữ kiện, chấm/nhận xét nhất quán và tránh thưởng cho hình thức ngoài mục tiêu không. Nếu yêu cầu tạo rubric chuyên sâu hoặc phản biện thiết kế, phối hợp skill chuyên biệt có sẵn, giữ một bộ mục tiêu và quy tắc chung; không mở rộng mọi slide luyện tập thành đề thi.
- Với đáp án cần xuất hiện sau, dùng slide tách hoặc cơ chế hiển thị đã kiểm tra. Không coi nội dung trong ghi chú là đang hiển thị trên màn hình hoặc hứa có hiệu ứng chưa xác minh.
- Tránh phụ thuộc Internet, video, âm thanh, phông hoặc phần bổ trợ chưa xác nhận. Nếu cần tài nguyên ngoài, kiểm tra điều kiện sử dụng và chuẩn bị phương án tĩnh khả dụng trong phạm vi công việc.

## 4. Tạo tệp và kiểm tra

- Dùng skill Presentations cho thao tác tệp và quy trình thiết kế, dựng slide, kiểm tra hiển thị. Dùng công cụ thật sự có trong môi trường; không tự khẳng định đã thao tác trong PowerPoint hoặc kiểm tra trình chiếu nếu chỉ tạo tệp.
- Bàn giao `.pptx` có thể chỉnh sửa khi được yêu cầu và công cụ hỗ trợ; không thay bằng HTML/PDF rồi gọi là PowerPoint. Nếu không thể xuất, nói rõ giới hạn và định dạng đã tạo thực tế.
- Ưu tiên văn bản, hình khối, bảng và biểu đồ chỉnh sửa được; không raster hóa toàn bộ slide để che vấn đề bố cục. Giữ ảnh bản đồ/hình gốc khi phù hợp và không tuyên bố chúng là dữ liệu chỉnh sửa được.
- Xem từng slide sau lần chỉnh cuối: chữ cắt/tràn, chồng đối tượng, lỗi tiếng Việt, tương phản, kích thước chú giải, hình méo hoặc mờ, số liệu và trật tự câu hỏi–đáp án. Kiểm tra ghi chú và liên kết mà nhiệm vụ cần.
- Xác minh tính năng tương tác hoặc hiệu ứng nếu đã cam kết; nếu môi trường không kiểm tra được, ghi rõ và dùng phương án đơn giản có thể kiểm tra khi có thể.
- Đối chiếu lại với giáo án/phiếu được dùng: mục tiêu, mã hoạt động, dữ kiện, thuật ngữ, câu hỏi và đáp án. Mọi thay đổi dữ kiện dùng chung cần rà sản phẩm phụ thuộc trong phạm vi nhiệm vụ.
- Tách tài liệu giáo viên và học sinh nếu được yêu cầu. Bản phát học sinh không lộ ghi chú, đáp án hoặc slide ẩn của bản giáo viên; không coi “ẩn slide” là đã loại nội dung khỏi tệp.

## 5. Bàn giao và chỉnh sửa

- Giữ tệp gốc, lưu bản mới có tên dễ hiểu. Bàn giao liên kết PowerPoint và chỉ những bản PDF/phiếu/bản học sinh đã được yêu cầu.
- Tóm tắt nội dung, cách dùng ghi chú/slide đáp án khi có, kiểm tra thực hiện được và phần còn hạn chế. Không gọi bài giảng “đã được giáo viên duyệt” khi chưa có phê duyệt.
- Khi sửa một phần, giữ thiết kế đã chấp thuận trừ khi thay đổi đó là yêu cầu; rà lại slide và dữ liệu liên quan. Không xin duyệt lại các chi tiết nhỏ đã nằm trong phạm vi chỉnh sửa.
- Câu hỏi luyện tập trong bài có đáp án hỗ trợ giảng dạy; đề kiểm tra chính thức và barem của đề đó thuộc skill ra đề. Rubric độc lập cho thực hành/dự án thuộc skill thiết kế rubric; việc cho điểm bài học sinh theo barem thuộc skill chấm bài.

## 6. Chế độ chuẩn bị lên lớp bằng slide — chỉ khi được yêu cầu

- Chỉ kích hoạt khi giáo viên muốn cùng thử nhiệm vụ, tập dẫn dắt hoặc chuẩn bị cách triển khai, không tự hỏi đáp sau mọi lần tạo PowerPoint. Dùng [references/chuan-bi-len-lop.md](references/chuan-bi-len-lop.md).
- Đọc slide/ghi chú và giáo án liên quan thực có; tự thử nhiệm vụ trọng tâm. Cho giáo viên xem đúng câu hỏi và học liệu, mời họ thử trả lời và dự kiến chỗ học sinh dễ nhầm trước khi đưa đáp án/gợi ý của mình; nếu giáo viên muốn xem phân tích ngay, đáp ứng và ghi đúng hình thức trao đổi.
- Mỗi lượt tập trung một điểm triển khai. Dựa trên phản hồi, đề xuất câu hỏi gợi mở, xử lý lỗi hoặc chuyển hoạt động; nói rõ lỗi chuyên môn nếu có bằng căn cứ cụ thể. Không tự khẳng định đã trình chiếu/tập chạy hiệu ứng nếu chỉ đọc tệp.
- Kết thúc bằng ghi chú ngắn riêng cho giáo viên theo mạch bài, gắn mã slide/hoạt động và vấn đề còn mở. Nếu đã chuẩn bị cùng skill giáo án, tiếp tục hồ sơ đó, không tạo một phiên lặp lại. Chỉ cập nhật tệp slide/ghi chú khi giáo viên yêu cầu hoặc đã giao việc đó rõ ràng.

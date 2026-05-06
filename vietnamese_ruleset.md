Dạo này mình thấy rất nhiều bạn bắt đầu tiếp cận Antigravity Coding - tức là để AI agent tự viết code, tự chạy, tự sửa lỗi mà gần như không cần can thiệp thủ công.

Nghe rất hấp dẫn. Nhưng thực tế, đa số beginners đều mắc phải những lỗi giống nhau — khiến AI làm việc kém hiệu quả, thậm chí phá code thay vì fix code.

Lỗi 1: Prompt quá mơ hồ
"Làm cho cái app của tôi chạy được" — AI không phải thần thánh. Nó cần biết app là gì, lỗi ở đâu, ngữ cảnh ra sao.

Cách fix: cung cấp đủ ngữ cảnh — mô tả tính năng, dán thông báo lỗi cụ thể, nói rõ tech stack đang dùng.

Lỗi 2: Để agent chạy không có kiểm soát
Nhiều bạn bật agent lên rồi quay đi làm việc khác, quay lại thấy AI đã xóa sạch vài file, viết lại toàn bộ logic theo cách hoàn toàn khác.

Cách fix: dùng Plan Mode trước — bắt AI lên kế hoạch, bạn duyệt rồi mới cho chạy. Kiểm soát từng bước quan trọng.

Lỗi 3: Không có "Memory"
Agent không có bộ nhớ về dự án của bạn. Mỗi phiên làm việc nó bắt đầu lại từ đầu.

Cách fix: thiết lập file Rules ngay từ đầu — ghi rõ cấu trúc dự án, quy tắc code, các thư viện đang dùng. Đây là tài liệu bàn giao cho AI mỗi khi nó "thức dậy".

Lỗi 4: Tin tưởng AI 100% mà không kiểm tra lại
AI có thể tự tin viết code sai hoàn toàn logic nghiệp vụ mà không hề báo lỗi.

Cách fix: luôn xem lại những gì AI thay đổi qua diff hoặc git. Đừng bỏ qua bước này dù code có chạy được. Nếu được, nên viết Docs cho dự án của bạn.

Lỗi 5: Nhét hết mọi thứ vào 1 prompt
"Viết cho tôi cả hệ thống quản lý bán hàng, có đăng nhập, giỏ hàng, thanh toán, báo cáo..." — agent sẽ bắt đầu, rồi lạc giữa chừng, làm thiếu hoặc làm sai.

Cách fix: chia nhỏ task. Mỗi lần chỉ giao 1 tính năng cụ thể, xác nhận xong mới đến cái tiếp theo. Sử dụng Skill và Workflow để tái sử dụng prompt.

---

Antigravity Coding không có nghĩa là bạn không cần làm gì. Nó có nghĩa là bạn làm ít hơn, thông minh hơn — nhưng vẫn cần biết cách dẫn dắt AI đúng hướng.
# Quy định làm bài (RULES)

## 1. Hình thức làm bài
- Lab là bài tập **cá nhân**.
- Mỗi học viên tự làm trên repository của mình và nộp link repository cá nhân lên Codelab.
- Không làm bài theo nhóm, không dùng chung repository.

## 2. Quy định sử dụng AI
- Được phép sử dụng AI (như ChatGPT, Claude, GitHub Copilot, Cursor...) làm trợ lý học tập, giải thích khái niệm, gợi ý cú pháp và hỗ trợ debug.
- Học viên phải hiểu rõ toàn bộ mã nguồn và logic do mình nộp.
- Tự viết các nội dung phân tích, failure analysis, 5 Whys và reflection.
- Khi coach vấn đáp hoặc review, nếu học viên **không giải thích được** mã nguồn hoặc nội dung bài làm của mình, phần tương ứng sẽ bị **hủy điểm (0 điểm phần đó)**.

## 3. Hợp tác và Đạo văn
- Khuyến khích thảo luận ý tưởng, phương pháp tiếp cận và kỹ thuật đánh giá giữa các học viên.
- **Nghiêm cấm** sao chép trực tiếp mã nguồn, dữ liệu golden dataset hoặc nội dung reflection từ học viên khác.
- Trường hợp phát hiện đạo văn (plagiarism), **cả hai bên liên quan đều nhận 0 điểm** cho toàn bộ bài lab.

## 4. Bảo mật thông tin
- **Tuyệt đối không commit** file `.env`, API key (như `OPENROUTER_API_KEY`), access tokens hoặc bất kỳ thông tin bí mật nào lên GitHub repository.
- File `.env` đã được đưa vào `.gitignore`. Hãy kiểm tra kỹ trước khi `git add` và `git push`.
- Vi phạm commit secret / API key lên repository sẽ bị **trừ 10 điểm (-10)**.

## 5. Thời hạn nộp bài và Nộp muộn
- **Hạn chót mặc định:** 23h59 ngày diễn ra lab (GMT+7).
- Coach có thể gia hạn tối đa không quá 48 giờ (≤48h) cho các trường hợp đặc biệt có lý do chính đáng được phê duyệt trước.

## 6. Quy định Bonus
- Điểm thưởng (Bonus) chỉ được tính sau khi đã hoàn thành các yêu cầu bắt buộc của bài lab.
- Tổng bonus của bài lab tối đa **10 điểm** (Exercise 3.4 +5, Exercise 3.5 +5). Đây là điểm sản phẩm lab, không phải điểm giơ tay / pitching.
- Bonus cộng vào tổng điểm lab nhưng tổng điểm cuối cùng không vượt quá 100 (hoặc theo quy chế tính điểm của khóa học).

---

## Tài liệu liên quan
- [README.md](README.md) — Tổng quan bài lab và hướng dẫn khởi động
- [SUBMISSION.md](SUBMISSION.md) — Hướng dẫn nộp bài, định dạng tên repo và checklist
- [RUBRIC.md](RUBRIC.md) — Tiêu chí chấm điểm chi tiết và các trường hợp trừ điểm
- [CHECKPOINTS.md](CHECKPOINTS.md) — Hướng dẫn từng checkpoint và tiêu chuẩn nghiệm thu

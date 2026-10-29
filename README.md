# Biên tập footage thành video

Biến video quay sẵn thành kế hoạch dựng rõ mốc thời gian, nhịp, phụ đề, cảnh cần bỏ và đầu ra cần duyệt.

## Skill này giúp gì?

Skill dành cho video đã quay hoặc bản ghi có sẵn. Agent xem mô tả, transcript hoặc footage mà người dùng cung cấp; xác định đoạn đáng giữ; lập danh sách cắt với timecode; viết phụ đề/caption và bàn giao hướng dựng. Nó chỉ sửa/xuất video nếu phiên có công cụ được hỗ trợ và file đầu vào đã được truy cập thành công.

## Nội dung gói

- `SKILL.md`: quy trình chi tiết, đầu vào, đầu ra và tiêu chí tự kiểm tra.
- `README.md`: hướng dẫn cài và prompt bắt đầu.
- `LICENSE`: giấy phép MIT.

## Cách cài và dùng

1. Tải ZIP rồi giải nén; giữ nguyên thư mục có `SKILL.md`.
2. Mở phần Skills/Agent Skills của ứng dụng AI đang dùng và thêm thư mục hoặc tải gói theo hướng dẫn trong ứng dụng. Nếu ứng dụng chưa hỗ trợ nạp skill, dán nội dung `SKILL.md` vào chỉ dẫn của một cuộc trò chuyện/dự án và dùng prompt mẫu bên dưới.
3. Bắt đầu cuộc trò chuyện bằng mục tiêu, người xem, nền tảng, giới hạn và tệp tham chiếu bạn có quyền sử dụng. Không gửi mật khẩu, mã xác minh, token hoặc dữ liệu khách hàng không cần thiết.
4. Đọc phần **Giả định** và **Cần người dùng duyệt**. Kiểm tra kỹ quyền dùng tài nguyên, dữ liệu, giá và quy định hiện hành trước khi tạo tệp tốn phí hoặc đăng công khai.
5. Lặp lại bằng cách nêu một thay đổi cụ thể; yêu cầu Agent giữ nguyên những phần đã duyệt.

Cách nạp skill khác nhau giữa ứng dụng và tài khoản. Hãy làm theo giao diện hiện hành của ChatGPT, Claude hoặc Agent khác; đừng giả định một nút cài đặt giống nhau có ở mọi gói.

## Prompt bắt đầu

> Dựa trên transcript có timecode và video phỏng vấn tôi gửi, hãy đề xuất bản dọc tối đa 60 giây về [chủ đề]. Trả bảng in/out, lý do giữ/cắt, đoạn có nguy cơ mất ngữ cảnh, phụ đề đã rà, vị trí B-roll và checklist QC. Đánh dấu timecode nào là ước lượng; không tự nhận đã dựng file nếu chưa có công cụ xuất video.

## Tác giả và watermark

Biên soạn: [cachdungai.blog](https://cachdungai.blog/)

Gói được phân phối miễn phí theo điều khoản trong `LICENSE`. Kết quả tạo media có thể cần công cụ, tài khoản hoặc chi phí riêng; hãy duyệt đầu ra trước khi dùng công khai.

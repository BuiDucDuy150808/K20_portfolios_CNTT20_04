# Ghi chú phát hành và bàn giao

## Thông tin phiên bản

- **Tên sản phẩm:** Website Portfolio cá nhân – Bùi Đức Duy (Lab 5).
- **Phiên bản hồ sơ:** V8.
- **Ngày cập nhật ghi chú:** 06/11/2026.
- **Ngày cập nhật mã nguồn được nộp:** 05/11/2026.
- **Nhánh và mã nguồn chính xác:** `main` tại commit
  [`d9ec3111dc18fea80a471988b2b3d62242525f1e`](https://github.com/BuiDucDuy150808/K20_portfolios_CNTT20_04/commit/d9ec3111dc18fea80a471988b2b3d62242525f1e).
  Tại thời điểm lập ghi chú, `main` và `origin/main` cùng trỏ tới commit này.
- **Demo:** [Portfolio trên GitHub Pages](https://buiducduy150808.github.io/K20_portfolios_CNTT20_04/).

> **Lưu ý về nhãn phiên bản:** Hai Git tag `v7` và `v8` hiện cùng trỏ tới
> commit `5bc6dde375cb58c5143e834748ce32ef803b5192`, không phải commit mới nhất
> trên `main`. Khi kiểm tra hoặc bàn giao mã đã nộp, dùng liên kết commit đầy đủ
> ở trên thay vì chỉ dựa vào tên tag.

## Thay đổi chính

- Hoàn thiện portfolio HTML/CSS responsive, các mục điều hướng, kỹ năng, dự án,
  lộ trình học tập và biểu mẫu liên hệ mô phỏng.
- Sắp xếp hồ sơ bàn giao, bổ sung hướng dẫn chạy, bảng minh chứng và nhật ký AI.
- Đưa website lên GitHub Pages.
- Ở commit nộp `d9ec311`, cập nhật lời chào từ tên mẫu “An” thành “Duy”.

## Lỗi đã sửa

- Không có lỗi chức năng cụ thể nào được ghi nhận là đã sửa trong lịch sử bàn giao.
- Thay đổi mã gần nhất sửa nội dung tên mẫu “An” thành “Duy”; đây là chỉnh sửa
  nội dung, không phải bản sửa lỗi chức năng.

## Kiểm tra đã thực hiện

Theo [bảng minh chứng](docs/evidence-index.md):

- Mở website bằng cửa sổ ẩn danh và kiểm tra nội dung, ảnh, CSS.
- Bấm các mục menu và xác nhận điều hướng tới đúng phần.
- Kiểm tra cuộn trang ở chiều rộng 375 px.

## Hạn chế còn lại

- Chưa kiểm tra thực tế trên iPhone/Safari.
- Biểu mẫu chỉ mô phỏng kiểm tra dữ liệu bằng HTML và chuyển sang trang kết quả
  qua GET; chưa gửi email, lưu dữ liệu hoặc xử lý phía máy chủ. Chỉ dùng dữ liệu
  giả khi thử biểu mẫu.
- Minh chứng hiện có là tự kiểm tra thủ công; chưa ghi nhận kết quả kiểm thử tự
  động.

## Cách tiếp tục kiểm tra và bàn giao

1. Mở liên kết commit chính xác ở phần **Thông tin phiên bản**; khi kiểm tra bản
   sao local, chạy `git rev-parse HEAD` và xác nhận nhận được
   `d9ec3111dc18fea80a471988b2b3d62242525f1e`.
2. Mở [bản demo](https://buiducduy150808.github.io/K20_portfolios_CNTT20_04/),
   kiểm tra menu, liên kết nội bộ và giao diện ở màn hình rộng lẫn 375 px.
3. Thử biểu mẫu với trường bắt buộc để trống, email sai định dạng, tên ngắn hơn
   2 ký tự và nội dung ngoài giới hạn 10–500 ký tự; xác nhận trình duyệt chặn dữ
   liệu không hợp lệ. Không nhập thông tin cá nhân thật.
4. Kiểm tra thêm trên iPhone/Safari và ghi kết quả vào
   [bảng minh chứng](docs/evidence-index.md).
5. Khi bàn giao, nêu rõ demo chỉ là biểu mẫu mô phỏng và dùng commit SHA đầy đủ
   ở trên làm mốc đối chiếu mã nguồn.
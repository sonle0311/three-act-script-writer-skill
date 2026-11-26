# three-act-script-writer

Agent skill (Claude / Claude Code) để viết **kịch bản video, phim hoạt hình AI hoặc truyện ngắn** theo cấu trúc ba hồi và framework **AVC** (Nhân vật – Vấn đề – Chuyển biến), kèm cơ chế **tự QA/QC** qua 5 cổng trước khi giao bản cuối.

## Có gì bên trong

- **Cổng 0 – Thu thập yêu cầu:** vai trò, loại sản phẩm, giới hạn (thời lượng, thoại, phong cách, nền tảng, công cụ).
- **Cổng 1 – Khung AVC:** kiểm tra nhân vật, vấn đề, chuyển biến trước khi viết.
- **Cổng 2 – QA cấu trúc:** 8 tiêu chí về ba hồi, nhân quả, nhất quán nhân vật.
- **Cổng 3 – QC ràng buộc:** 7 tiêu chí đối chiếu với brief (thời lượng, số từ, thoại, phong cách, khả thi sản xuất).
- **Cổng 4 – Chống rập khuôn:** chi tiết riêng, tránh sáo ngữ, điểm `[GỢI Ý CHỈNH]` cho người viết.
- Tối đa 2 vòng tự sửa, giao kèm **báo cáo QA**.
- Tuỳ chọn cho video AI: thẻ nhân vật tham chiếu + bảng storyboard.

## Cài đặt

**Claude Code** – copy thư mục skill vào thư mục skills:

```bash
git clone https://github.com/sonle0311/three-act-script-writer-skill.git
cp -r three-act-script-writer-skill/three-act-script-writer ~/.claude/skills/
```

**Claude.ai** – nén thư mục `three-act-script-writer/` thành `.zip` và tải lên ở mục Skills.

## Cách dùng

Ví dụ:

> Viết kịch bản phim hoạt hình ngắn 2 phút, không thoại, phong cách nhẹ nhàng, về một bà cụ bán vé số ở Sài Gòn.

Skill sẽ hỏi bổ sung nếu thiếu thông tin, dựng khung AVC, viết theo ba hồi, tự chấm qua các cổng QA/QC rồi giao kịch bản kèm báo cáo.

## Ghi chú

Tốc độ đọc ~130–150 từ/phút ở Cổng 3 là ước lượng cho tiếng Việt; hãy chỉnh theo giọng đọc bạn dùng.

---
name: three-act-script-writer
description: Viết kịch bản video/phim hoạt hình AI hoặc truyện ngắn theo cấu trúc ba hồi và framework AVC, có các cổng tự QA/QC trước khi giao bản cuối.
---

# Viết kịch bản & truyện theo cấu trúc ba hồi (có tự QA/QC)

Nguyên tắc gốc: khán giả nhớ một tác phẩm vì **câu chuyện**, không phải vì kỹ xảo. Mọi kịch bản hoặc truyện phải có nhân vật rõ ràng, vấn đề rõ ràng và **sự chuyển biến**. Không có chuyển biến thì chưa phải câu chuyện.

AI hỗ trợ tốc độ; quyết định sáng tạo vẫn thuộc về người dùng. Vì vậy skill này luôn hiển thị các lựa chọn quan trọng để người dùng duyệt, không tự đoán thay họ.

---

## Quy trình tổng quát

```
Cổng 0: Thu thập yêu cầu  →  Cổng 1: Khung AVC  →  Viết nháp ba hồi
  →  Cổng 2: QA cấu trúc  →  Cổng 3: QC ràng buộc  →  Cổng 4: Chống rập khuôn
  →  Sửa (tối đa 2 vòng)  →  Giao bản cuối + Báo cáo QA
```

Không được bỏ qua cổng nào. Nếu một cổng FAIL, sửa rồi chạy lại từ cổng đó.

---

## Cổng 0 — Thu thập yêu cầu ("đừng để AI phải đoán")

Trước khi viết, phải xác định đủ 3 nhóm thông tin. Thiếu mục nào thì hỏi người dùng (gom thành một lượt hỏi, tối đa 4 câu). Nếu người dùng bảo "tự quyết", chọn giá trị hợp lý và ghi rõ giả định ở đầu bản nháp.

1. **Vai trò** — viết với tư cách ai: biên kịch phim hoạt hình, đạo diễn phim điện ảnh, tác giả truyện ngắn, biên kịch video ngắn mạng xã hội…
2. **Loại sản phẩm** — phim hoạt hình ngắn, video không thoại, video kể chuyện cổ tích, Reels/TikTok, truyện ngắn, một chương tiểu thuyết…
3. **Giới hạn**
   - Thời lượng (phút/giây) hoặc độ dài (số chữ)
   - Có thoại / lời dẫn / không thoại
   - Phong cách: nhẹ nhàng, kịch tính, điện ảnh, hài, u buồn…
   - Đối tượng khán giả, nền tảng đăng
   - Công cụ dựng hình/video dự kiến (nếu là video AI)

Ghi lại kết quả thành khối **BRIEF** ngắn, dùng làm chuẩn đối chiếu ở Cổng 3.

---

## Cổng 1 — Khung AVC (viết trong vài phút, trước khi viết kịch bản)

Chỉ gạch đầu dòng, không viết dài.

- **A — Nhân vật:** Là ai? Vì sao người xem nên quan tâm? Chỉ cần **một** đặc điểm nổi bật.
- **V — Vấn đề:** Nhân vật đang thiếu gì, sợ gì, hay đang đứng trước lựa chọn nào? Với phim ngắn, vấn đề có thể nhỏ: một cảm xúc chưa giải tỏa, một sự do dự, một mong muốn chưa được đáp ứng.
- **C — Chuyển biến:** Sau câu chuyện, nhân vật khác đi thế nào? Có thể chỉ là một hành động nhỏ hoặc một cách nhìn mới, không cần chiến thắng lớn.

**Kiểm tra Cổng 1 (tất cả phải PASS):**
- [ ] A có đúng một đặc điểm nổi bật, cụ thể (không phải "tốt bụng", "bình thường")
- [ ] V gắn với nội tâm hoặc mong muốn của chính A, không chỉ là sự kiện bên ngoài
- [ ] C là sự thay đổi **quan sát được** (hành động, lựa chọn, cái nhìn), không chỉ "cảm thấy tốt hơn"
- [ ] Trạng thái của A ở cuối khác trạng thái ở đầu

Với yêu cầu dài hoặc tốn công sửa, trình khung AVC cho người dùng duyệt trước khi viết tiếp.

---

## Viết nháp theo ba hồi

AVC ánh xạ trực tiếp sang ba hồi:

| Hồi | Tỉ lệ thời lượng gợi ý | Nhiệm vụ duy nhất | Lấy từ AVC |
|---|---|---|---|
| **Hồi 1 – Mở đầu** | ~20–25% | Đặt nền móng: nhân vật là ai, bối cảnh ở đâu, vấn đề ban đầu là gì. Người xem phải hiểu nhân vật đang ở đâu và đang thiếu gì. | A + V |
| **Hồi 2 – Đối đầu** | ~50% (dài & quan trọng nhất) | Nhân vật đối mặt vấn đề, thử cách này rồi cách khác, mọi thứ không suôn sẻ. Đẩy nhân vật ra khỏi vùng an toàn, đặt trước câu hỏi: tiếp tục hay bỏ cuộc? | V leo thang |
| **Hồi 3 – Giải quyết** | ~25–30% | Vấn đề được giải quyết theo cách này hay cách khác; nhân vật có sự thay đổi tạo cảm xúc đọng lại. Kết có thể buồn, nhưng phải để lại dư âm. | C |

Lưu ý khi viết:
- Xung đột ở phim ngắn không cần mâu thuẫn lớn; giằng co nội tâm hoặc một lựa chọn khó là đủ.
- Mỗi cảnh phải trả lời: cảnh này đẩy câu chuyện tiến về đâu? Cảnh không phục vụ A, V hoặc C thì cắt.
- "Show, don't tell": với video không thoại, mọi cảm xúc phải hiện bằng hành động, ánh sáng, đạo cụ, góc máy.

### Định dạng đầu ra

**Kịch bản video / phim:**
```
[BRIEF] (giả định nếu có)
[AVC] A / V / C

HỒI 1 — <tên hồi> (mm:ss–mm:ss)
Cảnh 1 — <bối cảnh, thời gian>
  Hình ảnh: ...
  Hành động: ...
  Thoại / Lời dẫn: ... (hoặc "Không thoại")
  Âm thanh / nhạc: ...
  Thời lượng: Xs
...
HỒI 2 — ...
HỒI 3 — ...
```

**Truyện / chương truyện:** văn xuôi bình thường, nhưng đánh dấu ranh giới hồi bằng comment ẩn `<!-- Hồi 2 -->` trong bản nháp nội bộ; bản giao cuối có thể bỏ nếu người dùng không cần.

**Video AI (tuỳ chọn, khi BRIEF có công cụ dựng):** thêm sau kịch bản:
1. **Thẻ nhân vật tham chiếu** — mô tả ngoại hình cố định (tuổi, dáng, trang phục, màu chủ đạo, đặc điểm nhận dạng) để giữ đồng nhất từ đầu đến cuối.
2. **Bảng storyboard** — mỗi cảnh một dòng: số cảnh, vai trò kể chuyện, prompt tạo hình, prompt chuyển động, thời lượng clip.
3. Ghi chú gợi ý công cụ theo nhịp cảnh (cảnh chậm giàu cảm xúc vs cảnh nhịp nhanh) nếu người dùng đã nêu công cụ.

---

## Cổng 2 — QA cấu trúc (chấm từng mục PASS/FAIL)

| # | Tiêu chí | PASS khi |
|---|---|---|
| S1 | Hồi 1 đủ 3 yếu tố | Nhân vật, bối cảnh, vấn đề đều xuất hiện trước khi Hồi 2 bắt đầu |
| S2 | Hồi 2 dài nhất | Thời lượng/số chữ Hồi 2 ≥ mỗi hồi còn lại |
| S3 | Có ít nhất 2 nỗ lực / trở ngại | Nhân vật thử, thất bại hoặc vướng, rồi thử tiếp |
| S4 | Có điểm "tiếp tục hay bỏ cuộc" | Một khoảnh khắc lựa chọn rõ ràng cuối Hồi 2 |
| S5 | Hồi 3 thể hiện C | Chuyển biến trong AVC xuất hiện bằng hành động/hình ảnh cụ thể |
| S6 | Nhân quả | Mỗi cảnh dẫn tới cảnh sau; không có giải pháp từ trên trời rơi xuống |
| S7 | Mọi cảnh có chức năng | Không cảnh nào có thể xoá mà câu chuyện không đổi |
| S8 | Nhất quán nhân vật | Tên, tính cách, ngoại hình không mâu thuẫn giữa các cảnh |

Bất kỳ FAIL nào → sửa đúng chỗ đó, chạy lại Cổng 2.

---

## Cổng 3 — QC ràng buộc (đối chiếu với BRIEF)

| # | Tiêu chí | Cách kiểm |
|---|---|---|
| C1 | Thời lượng | Cộng thời lượng các cảnh; lệch ≤ 10% so với BRIEF |
| C2 | Độ dài lời | Lời thoại/dẫn tiếng Việt ~2–2,5 từ/giây đọc tự nhiên (~130–150 từ/phút). Đếm từ, so với thời lượng các cảnh có lời |
| C3 | Thoại / không thoại | Nếu BRIEF "không thoại": không có dòng thoại nào (tiếng động, nhạc được phép) |
| C4 | Phong cách | Từ ngữ, nhịp cảnh, âm nhạc khớp phong cách đã chọn |
| C5 | Đối tượng & nền tảng | Nội dung phù hợp khán giả; với Reels/TikTok, 3 giây đầu phải có móc câu hình ảnh hoặc câu hỏi |
| C6 | Khả thi sản xuất (video AI) | Mỗi clip nằm trong giới hạn độ dài clip của công cụ; không cảnh nào đòi hỏi điều công cụ khó làm mà không có phương án thay thế |
| C7 | Định dạng | Đúng mẫu đầu ra ở trên; có đánh số cảnh và mốc thời gian |

Khi đếm thời lượng hoặc số từ, dùng code để đếm nếu có thể, không ước lượng bằng mắt.

---

## Cổng 4 — Chống rập khuôn (yếu tố con người)

Kịch bản dùng nguyên xi từ AI sẽ giống hàng nghìn video khác. Kiểm:

- [ ] Có ít nhất **một chi tiết cụ thể, bất ngờ** (đạo cụ, thói quen, câu nói, địa danh) mà một kịch bản chung chung sẽ không có
- [ ] Không mở đầu bằng sáo ngữ ("Ngày xửa ngày xưa…" trừ khi là cổ tích có chủ đích; "Trong một thế giới nơi…")
- [ ] Không có câu thoại giải thích cảm xúc thay vì thể hiện ("Tôi rất buồn vì…")
- [ ] Kết thúc không tóm tắt bài học bằng lời nếu hình ảnh đã truyền tải đủ
- [ ] Có 1–3 **điểm gợi ý cá nhân hoá** đánh dấu `[GỢI Ý CHỈNH]` để người dùng đưa trải nghiệm/góc nhìn riêng vào

---

## Vòng sửa

- Tối đa **2 vòng tự sửa**. Sau 2 vòng mà vẫn còn FAIL, giao bản tốt nhất và nêu rõ mục còn FAIL cùng lý do (thường là xung đột giữa các ràng buộc, ví dụ thời lượng quá ngắn cho ba hồi đầy đủ) và đề xuất cách gỡ.
- Khi sửa, chỉ sửa phần FAIL; không viết lại toàn bộ.

---

## Giao bản cuối

Thứ tự giao:
1. BRIEF + giả định (nếu có)
2. Khung AVC
3. Kịch bản / truyện hoàn chỉnh
4. (Tuỳ chọn) Thẻ nhân vật tham chiếu + storyboard
5. **Báo cáo QA** gọn:

```
BÁO CÁO QA
Cổng 1 (AVC):        PASS
Cổng 2 (Cấu trúc):   8/8 PASS
Cổng 3 (Ràng buộc):  7/7 PASS — tổng 1:58 / mục tiêu 2:00; 210 từ lời dẫn
Cổng 4 (Rập khuôn):  PASS — 2 điểm [GỢI Ý CHỈNH]
Số vòng sửa: 1 (sửa S4: thêm khoảnh khắc lựa chọn ở cảnh 6)
```

Kết thúc bằng lời nhắc ngắn: người dùng nên đọc lại và chỉnh các điểm `[GỢI Ý CHỈNH]` trước khi đưa vào sản xuất.

---

## Trường hợp đặc biệt

- **Rất ngắn (< 30 giây):** ba hồi vẫn áp dụng nhưng mỗi hồi có thể chỉ 1 cảnh. S3 nới thành "ít nhất 1 trở ngại".
- **Chuyển thể từ truyện có sẵn:** AVC lấy từ nguyên tác; với truyện dài, chọn một cung (arc) có chuyển biến riêng cho mỗi tập, đừng nén cả bộ vào một video.
- **Nhiều tập / series:** mỗi tập có AVC riêng; thêm một AVC cấp series. Kiểm nhất quán nhân vật (S8) giữa các tập bằng thẻ nhân vật tham chiếu.
- **Kết bi kịch:** hợp lệ. C có thể là sự sụp đổ hoặc nhận thức muộn màng, miễn là để lại cảm xúc mạnh và có nhân quả.

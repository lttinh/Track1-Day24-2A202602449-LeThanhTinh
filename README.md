# Lab 24 — Kinh tế sản phẩm AI

## Thông tin cá nhân

- **Họ và tên:** Lê Thanh Tình
- **Mã sinh viên:** 2A202602449
- **Chương trình:** AI in Action — Track 1
- **Bài thực hành:** Day 24 — CS9 Workshop
- **Nhóm:** 3201

## Giới thiệu

Đây là bài thực hành phân tích **chi phí, định giá và hiệu quả đầu tư của sản phẩm AI**. Nhóm lựa chọn đề bài giả định **SổSạch** — trợ lý AI hỗ trợ văn phòng kế toán dịch vụ xử lý hóa đơn đầu vào.

Một đơn vị công việc được xác định là:

> Một hóa đơn đầu vào do khách hàng gửi được AI đọc, đối chiếu mã số thuế và nhập vào phần mềm kế toán. Các hóa đơn mờ, viết tay hoặc có giá trị trên 20 triệu đồng sẽ được chuyển cho kế toán viên kiểm tra.

## Cấu trúc thư mục

| Tệp | Mô tả |
|---|---|
| `Nhom3201_CS9.xlsx` | Bài làm chính của nhóm 3201 |
| `CS9_Workshop_Mau.xlsx` | File mẫu dùng để tham khảo cấu trúc và cách tính |
| `README.md` | Tài liệu giới thiệu và tóm tắt bài làm |

## Nội dung đã thực hiện

Workbook bài làm gồm các phần chính:

- Tổng hợp dữ liệu đầu vào và nguồn của từng giả định.
- Hoàn thành ba báo cáo tài chính căn bản.
- Tính chi phí xử lý một hóa đơn, bao gồm chi phí AI, kiểm tra thủ công và chi phí liên quan.
- Xây dựng phương án định giá theo gói tháng kết hợp phí vượt hạn mức.
- Phân tích ba kịch bản: lạc quan, cơ sở và xấu.
- Tính các chỉ số LTV/CAC, biên lợi nhuận gộp, dòng tiền, NPV và thời gian hoàn vốn trong 24 tháng.
- Phân tích độ nhạy và đề xuất ngưỡng cảnh báo để kiểm soát rủi ro.

## Phương án định giá

- **Phí thuê bao:** 1.990.000 đồng/tháng.
- **Hạn mức:** 1.000 hóa đơn/tháng.
- **Phí vượt hạn mức:** 2.200 đồng/hóa đơn.
- **Cơ cấu khách hàng giả định:** 70% văn phòng nhỏ và 30% văn phòng lớn.
- **Không áp dụng gói không giới hạn** vì nhóm khách hàng sử dụng nhiều có thể khiến chi phí AI vượt doanh thu.

## Kết quả chính

| Chỉ số | Kịch bản cơ sở | Kịch bản xấu |
|---|---:|---:|
| Chi phí mỗi hóa đơn | 704 đồng | — |
| Biên lợi nhuận gộp | 68,8% | 53,2% |
| LTV/CAC | 10,1 lần | 2,6 lần |
| Thời gian hoàn vốn CAC | 3,3 tháng | 8,0 tháng |
| NPV trong 24 tháng | +935 triệu đồng | −5,0 tỷ đồng |
| Tiền mặt thấp nhất | 173 triệu đồng | −3,09 tỷ đồng |
| Kết quả vận hành | Hoàn vốn tháng 21 | Hết tiền tháng 7 |

Doanh thu bình quân trên mỗi khách hàng là biến nhạy cảm nhất. Nếu chỉ số này giảm khoảng 6,5%, xuống dưới **3,71 triệu đồng/tháng**, dự án sẽ tiến gần điểm hòa vốn hoặc chuyển sang không hiệu quả.

## Quyết định đề xuất

### Thử nghiệm nhỏ

Kịch bản cơ sở cho thấy sản phẩm có tiềm năng sinh lời, nhưng kịch bản xấu tạo ra rủi ro dòng tiền lớn. Vì vậy, nhóm chưa triển khai toàn diện mà đề xuất:

1. Thử nghiệm trong 3 tháng với 12 văn phòng kế toán.
2. Chỉ mở rộng khi doanh thu bình quân đạt ít nhất 3,71 triệu đồng/khách hàng/tháng và tỷ lệ rời bỏ không vượt quá 3%/tháng.
3. Nếu doanh thu bình quân dưới 3,714 triệu đồng hoặc tỷ lệ rời bỏ trên 4,8% trong hai tháng liên tiếp, dừng thu hút khách hàng mới và triển khai kế hoạch cắt giảm chi phí.
4. Không hạ phí vượt hạn mức xuống dưới 2.113 đồng/hóa đơn và không bán gói không giới hạn.

## Lưu ý

- Các số liệu của sản phẩm SổSạch được xây dựng từ đề bài giả định và được ghi nguồn trong workbook.
- `CS9_Workshop_Mau.xlsx` chỉ dùng để tham khảo, không phải tệp nộp bài.
- Tệp cần nộp trên VLearn là `Nhom3201_CS9.xlsx`.

---

**Thực hiện:** Lê Thanh Tình — 2A202602449

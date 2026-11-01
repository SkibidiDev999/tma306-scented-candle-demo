# ATELIER LUMEN | Đồ Án Thương Mại Điện Tử TMA306

Dự án nghiên cứu và triển khai website thương mại điện tử Direct-to-Consumer (D2C) cho sản phẩm nến thơm thủ công cá nhân hóa định danh, thuộc học phần **Thương mại điện tử (TMA306) - Đại học Ngoại Thương**.

---

## 1. Mục Tiêu & Cơ Sở Học Thuật
* **8 thành tố mô hình kinh doanh TMĐT (Laudon & Traver):** Vận hành mô hình B2C D2C E-tailer với biên lợi nhuận gộp cao, kết hợp đa dạng hóa nguồn thu: Bán nến lẻ cốt lõi, phụ phí in dập nhãn thủ công theo yêu cầu, bán chéo combo dụng cụ chăm sóc nến và chính sách kinh tế tuần hoàn Refill vỏ hũ cũ giảm 20%.
* **Đánh giá chất lượng website theo mô hình 7C (Rayport & Jaworski):**
  * *Context:* Bố cục tinh giản chuẩn in ấn Thụy Sĩ (Swiss Style), viền hairline 1px, hỗ trợ kéo thả đổi cấu trúc khối (Page Builder).
  * *Content:* Minh bạch xuất xứ 100% sáp đậu nành Bến Tre, bấc gỗ phong Bắc Mỹ không ngâm hóa chất, thông số mẻ rót và kim tự tháp 3 tầng hương.
  * *Customization:* Bộ công cụ Bespoke 3D Studio xoay 360 độ và ánh xạ nhãn in động thời gian thực (Dynamic Canvas Texture Mapping).
  * *Community:* Lưu trữ biên bản đánh giá từ đơn hàng thực nghiệm.
  * *Commerce:* Giỏ hàng Drawer, voucher giảm giá Refill và cổng thanh toán mô phỏng VietQR Napas247.
  * *Communication & Connection:* Tích hợp bộ phát âm thanh bấc gỗ tí tách (Web Audio API) và liên kết bưu cục hẹn giờ giao quà ẩn danh.

---

## 2. Các Tiện Ích Web Chuyên Sâu (5 Web Extensions)
1. **Extension 1 (Bespoke 3D Studio):** Trực quan hóa mô hình hũ nến 3D bằng Three.js (r128), hỗ trợ xoay 360 độ, đổi vật liệu PBR (thủy tinh hổ phách, gốm Bát Tràng, khoáng terrazzo), đổi bấc (bấc gỗ phong, cotton hữu cơ) và ánh xạ nhãn dán thủ công thời gian thực (Dynamic Canvas Texture Mapping với thẻ `HAND-POURED ATELIER`).
2. **Extension 2 (Olfactory Consultation Quiz):** Trắc nghiệm tâm lý học khứu giác 6 câu hỏi chuyên sâu với thanh tiến trình trực quan, chẩn đoán nhu cầu phục hồi cảm xúc và tự động đề xuất 6 công thức hương Niche Perfumery độc bản (đầy đủ Kim tự tháp 3 tầng Top - Heart - Base notes, độ tỏa Sillage và thời lượng cháy 50h).
3. **Extension 3 (Tooling & Preservation Bundle):** Bộ công cụ chăm sóc nến mạ đồng thau cổ điển và hộp quà giấy dệt thủ công có thanh tính giá chiết khấu động và quà tặng mẻ nến thử nghiệm.
4. **Extension 4 (Acoustic Multi-Genre Synthesizer):** Động cơ âm thanh Web Audio API tổng hợp thời gian thực tiếng bấc gỗ tí tách kèm 6 thể loại âm cảnh thư giãn (Midnight Noir Jazz, Lofi Rain, Acoustic Bossa, Neo-Classical Piano, Ambient Zen, 432Hz Sleepwave) bù đắp rào cản giác quan trực tuyến.
5. **Extension 5 (Dispatch Protocol Scheduler):** Bộ chọn ngày giờ bàn giao bưu phẩm chính xác, tùy chọn đóng dấu niêm phong sáp và chế độ gửi quà ẩn danh tạo bất ngờ cho người nhận.

---

## 3. Bản Quyền & Triển Khai Thực Nghiệm
* **Sinh viên thực hiện:** Nhóm đồ án môn Thương mại điện tử TMA306.
* **Giảng dạy:** Bộ môn Thương mại điện tử - Đại học Ngoại Thương.
* **Nền tảng công nghệ:** HTML5 Semantic, Tailwind CSS, Three.js (WebGL PBR Shader), Lucide Icons, Web Audio API, Canvas Confetti.
* **Tiêu chuẩn bảo mật:** CSP nghiêm ngặt, xử lý DOM XSS an toàn, tạo mã VietQR Napas247 offline bằng thuật toán SVG nội bộ, không phụ thuộc dịch vụ theo dõi bên thứ ba.
* **Demo trực tuyến (Live Demo):** [https://skibididev999.github.io/tma306-scented-candle-demo/](https://skibididev999.github.io/tma306-scented-candle-demo/)

# [Bài thực hành 4] Phân tích kết quả học tập và đề xuất giải pháp cải thiện
## PROMPT HOÀN CHỈNH 

Bạn là một chuyên gia phân tích dữ liệu học tập và tư vấn giáo dục. Hãy thực hiện phân tích dựa ĐÚNG VÀO DỮ LIỆU ĐƯỢC CUNG CẤP DƯỚI ĐÂY theo đúng quy trình 4 bước (Chain-of-Thought):
1. Tính toán: Tính mức tăng, giảm điểm (chênh lệch) của từng sinh viên qua các tuần (Tuần 1 -> Tuần 2, Tuần 2 -> Tuần 3, và tổng chênh lệch từ Tuần 1 đến Tuần 3).
2. So sánh: So sánh kết quả học tập giữa các sinh viên qua từng mốc thời gian.
3. Nhận định: Xác định nhóm sinh viên có dấu hiệu sa sút và đưa ra tối đa 3 nhận định quan trọng (chỉ dựa trên dữ liệu, không tự suy diễn nguyên nhân ngoài dữ liệu).
4. Đề xuất: Đề xuất 3 giải pháp hỗ trợ học tập cụ thể.

Dữ liệu đầu vào:
- An: Tuần 1 = 8, Tuần 2 = 7, Tuần 3 = 5
- Bình: Tuần 1 = 7, Tuần 2 = 6, Tuần 3 = 4
- Chi: Tuần 1 = 9, Tuần 2 = 8, Tuần 3 = 8
- Dũng: Tuần 1 = 6, Tuần 2 = 5, Tuần 3 = 3
- Hà: Tuần 1 = 8, Tuần 2 = 8, Tuần 3 = 7

Yêu cầu đầu ra: Trình bày rõ ràng theo từng bước phân tích, bao gồm bảng tính toán chi tiết, nhóm sinh viên sa sút, 3 nhận định chính và 3 giải pháp cải thiện.

---
## Kết quả của AI

# BÁO CÁO PHÂN TÍCH DỮ LIỆU HỌC TẬP VÀ TƯ VẤN GIÁO DỤC

## 1. Tính toán
Bảng tính toán mức tăng, giảm điểm (chênh lệch) qua các tuần và tổng chênh lệch:

| Sinh viên | Tuần 1 | Tuần 2 | Tuần 3 | Chênh lệch (T1 -> T2) | Chênh lệch (T2 -> T3) | Tổng chênh lệch (T1 -> T3) | Điểm trung bình |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **An** | 8 | 7 | 5 | -1 | -2 | **-3** | 6.67 |
| **Bình** | 7 | 6 | 4 | -1 | -2 | **-3** | 5.67 |
| **Chi** | 9 | 8 | 8 | -1 | 0 | **-1** | 8.33 |
| **Dũng** | 6 | 5 | 3 | -1 | -2 | **-3** | 4.67 |
| **Hà** | 8 | 8 | 7 | 0 | -1 | **-1** | 7.67 |

---

## 2. So sánh
- **Tuần 1 (Khởi đầu):** 
  - **Chi** dẫn đầu với mức điểm cao nhất (9 điểm).
  - Tiếp theo là **An** và **Hà** cùng đạt 8 điểm, **Bình** đạt 7 điểm.
  - **Dũng** có kết quả thấp nhất lớp với 6 điểm. Khoảng cách điểm số giữa người cao nhất và thấp nhất là 3 điểm.
- **Tuần 2 (Giữa kỳ):** 
  - **Chi** và **Hà** cùng dẫn đầu với 8 điểm (Chi giảm 1 điểm, Hà giữ nguyên phong độ).
  - Các sinh viên còn lại (**An**, **Bình**, **Dũng**) đều đồng loạt giảm 1 điểm, thứ tự phân hóa giữ nguyên: **An** (7 điểm) > **Bình** (6 điểm) > **Dũng** (5 điểm).
- **Tuần 3 (Kết thúc):** 
  - **Chi** tiếp tục giữ vững vị trí số 1 (8 điểm), theo sau là **Hà** (7 điểm).
  - Nhóm **An** (5 điểm), **Bình** (4 điểm), và **Dũng** (3 điểm) tiếp tục giảm mạnh thêm 2 điểm, đẩy khoảng cách điểm số so với nhóm dẫn đầu lên mức 3 đến 5 điểm.

---

## 3. Nhận định
- **Nhóm sinh viên có dấu hiệu sa sút nghiêm trọng:** **An, Bình, Dũng** (cùng ghi nhận tổng mức giảm 3 điểm sau 3 tuần, điểm số ở Tuần 3 rơi xuống ngưỡng từ 3 đến 5 điểm).
- **3 Nhận định quan trọng (chỉ dựa trên dữ liệu):**
  1. **Toàn bộ lớp học không ghi nhận sự tăng trưởng:** Không có sinh viên nào có mức chênh lệch dương (tăng điểm) từ Tuần 1 đến Tuần 3; 100% sinh viên đều giữ nguyên hoặc giảm điểm.
  2. **Tốc độ suy giảm gia tăng ở giai đoạn sau:** Nhóm **An, Bình, Dũng** chịu mức sụt giảm mạnh hơn ở giai đoạn cuối (từ Tuần 2 sang Tuần 3 giảm 2 điểm, gấp đôi mức giảm ở giai đoạn đầu). Riêng **Dũng** có điểm số giảm tới 50% từ Tuần 1 (6 điểm) đến Tuần 3 (3 điểm).
  3. **Sự phân hóa thành tích rõ rệt:** Lớp tách thành hai nhóm rõ rệt. Nhóm duy trì kết quả tốt (**Chi, Hà**) chỉ giảm tối đa 1 điểm qua các mốc thời gian và giữ vững mức 7-8 điểm, trong khi nhóm sa sút (**An, Bình, Dũng**) liên tục tụt dốc và rơi xuống vùng điểm thấp.

---

## 4. Đề xuất
1. **Tổ chức phụ đạo chuyên sâu cho nhóm sa sút (An, Bình, Dũng):** Xây dựng kế hoạch kèm cặp trực tiếp để bù đắp các lỗ hổng kiến thức phát sinh từ Tuần 2 và Tuần 3. Đặc biệt ưu tiên hỗ trợ **Dũng** (đạt 3 điểm ở Tuần 3) để củng cố lại nền tảng kiến thức căn bản từ Tuần 1.
2. **Triển khai mô hình học tập "Đôi bạn cùng tiến":** Ghép cặp các sinh viên có thành tích ổn định, cao điểm (**Chi, Hà**) hỗ trợ các sinh viên có dấu hiệu sa sút sâu (**An, Bình, Dũng**) nhằm trao đổi phương pháp học và ôn luyện bài tập định kỳ.
3. **Thiết lập hệ thống kiểm tra và đánh giá ngắn hạn (Micro-assessment):** Áp dụng các bài kiểm tra ngắn giữa các tuần để phát hiện sớm ngay khi điểm số chớm giảm (như mốc giảm 1 điểm ở Tuần 2 của nhóm An, Bình, Dũng), giúp đưa ra điều chỉnh kịp thời trước khi điểm số tiếp tục lao dốc.
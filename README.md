# CNTT1-K-N-ng-Promting-v-i-AI-Session05_BTTH04


### PHẦN 1: PROMPT HOÀN CHỈNH (ỨNG DỤNG CHAIN-OF-THOUGHT)

Bạn có thể sử dụng đoạn prompt sau để đưa vào AI phân tích dữ liệu:


#### VAI TRÒ
Bạn là Trợ lý phân tích dữ liệu học tập chuyên nghiệp, có nhiệm vụ xử lý số liệu khách quan, trung thực và dựa hoàn toàn trên dữ liệu nguồn được cung cấp.

#### BỐI CẢNH & DỮ LIỆU ĐẦU VÀO
Bảng điểm kiểm tra của 5 sinh viên qua 3 tuần học lập trình:
- An: Tuần 1 = 8, Tuần 2 = 7, Tuần 3 = 5
- Bình: Tuần 1 = 7, Tuần 2 = 6, Tuần 3 = 4
- Chi: Tuần 1 = 9, Tuần 2 = 8, Tuần 3 = 8
- Dũng: Tuần 1 = 6, Tuần 2 = 5, Tuần 3 = 3
- Hà: Tuần 1 = 8, Tuần 2 = 8, Tuần 3 = 7

#### YÊU CẦU PHÂN TÍCH TỪNG BƯỚC (CHAIN-OF-THOUGHT)
Hãy thực hiện tuần tự theo 4 bước sau và chỉ sử dụng đúng dữ liệu trên, tuyệt đối không tự suy diễn nguyên nhân ngoài dữ liệu:
1. Bước 1 (Tính toán): Tính mức thay đổi điểm số của từng sinh viên qua các giai đoạn (Tuần 1 -> Tuần 2, Tuần 2 -> Tuần 3, và tổng chênh lệch từ Tuần 1 đến Tuần 3).
2. Bước 2 (So sánh): Xếp hạng điểm số trung bình hoặc xu hướng biến động điểm số giữa các sinh viên.
3. Bước 3 (Nhận định & Xác minh): Xác định nhóm sinh viên có dấu hiệu điểm số giảm dần liên tục qua các tuần, đồng thời nêu các vấn đề cụ thể cần giảng viên xác minh thêm dựa trên số liệu.
4. Bước 4 (Đề xuất giải pháp): Đề xuất 3 giải pháp hỗ trợ học tập thực tế, cụ thể dựa trên xu hướng điểm số đã phân tích.

#### YÊU CẦU ĐẦU RA
Trình bày kết quả rõ ràng, súc tích gồm: Bảng phân tích kết quả, danh sách sinh viên sa sút, 3 nhận định quan trọng từ dữ liệu, và 3 giải pháp hỗ trợ học tập.



### PHẦN 2: BẢNG PHÂN TÍCH KẾT QUẢ CỦA 5 SINH VIÊN

| Sinh viên | Tuần 1 | Tuần 2 | Tuần 3 | Biến động (T1 $\rightarrow$ T2) | Biến động (T2 $\rightarrow$ T3) | Tổng chênh lệch (T1 $\rightarrow$ T3) | Xu hướng học tập |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **An** | 8 | 7 | 5 | -1 | -2 | -3 | Giảm liên tục |
| **Bình** | 7 | 6 | 4 | -1 | -2 | -3 | Giảm liên tục |
| **Chi** | 9 | 8 | 8 | -1 | 0 | -1 | Giảm nhẹ sau đó chững lại |
| **Dũng** | 6 | 5 | 3 | -1 | -2 | -3 | Giảm liên tục |
| **Hà** | 8 | 8 | 7 | 0 | -1 | -1 | Ổn định sau đó giảm nhẹ |

---

### PHẦN 3: XÁC ĐỊNH NHÓM SINH VIÊN CÓ DẤU HIỆU SA SÚT

* **Nhóm sinh viên có dấu hiệu sa sút rõ rệt (Điểm số giảm đều qua các tuần):**
* **An:** Giảm từ 8 (Tuần 1) $\rightarrow$ 7 (Tuần 2) $\rightarrow$ 5 (Tuần 3). Tổng giảm 3 điểm.
* **Bình:** Giảm từ 7 (Tuần 1) $\rightarrow$ 6 (Tuần 2) $\rightarrow$ 4 (Tuần 3). Tổng giảm 3 điểm.
* **Dũng:** Giảm từ 6 (Tuần 1) $\rightarrow$ 5 (Tuần 2) $\rightarrow$ 3 (Tuần 3). Tổng giảm 3 điểm.


* *Nhóm sinh viên biến động nhẹ:* Chi (giảm 1 điểm ở tuần 2 và giữ nguyên ở tuần 3) và Hà (giữ nguyên ở 2 tuần đầu và giảm 1 điểm ở tuần 3).

---

### PHẦN 4: BA NHẬN ĐỊNH QUAN TRỌNG TỪ DỮ LIỆU

1. **Xu hướng suy giảm diện rộng:** Toàn bộ 5 sinh viên (100% sĩ số) đều ghi nhận mức điểm ở Tuần 3 thấp hơn hoặc bằng Tuần 1, không có sinh viên nào có điểm số tăng trưởng xuyên suốt qua 3 tuần.
2. **Nhóm giảm điểm nghiêm trọng nhất:** An, Bình và Dũng có cùng mẫu số suy giảm điểm số giống hệt nhau qua các tuần (-1 điểm ở tuần 2 và -2 điểm ở tuần 3, tổng mức giảm là 3 điểm).
3. **Phân hóa kết quả học tập:** Chi luôn duy trì vị trí dẫn đầu lớp qua các tuần (9 $\rightarrow$ 8 $\rightarrow$ 8), trong khi Dũng luôn có mức điểm thấp nhất lớp qua các tuần (6 $\rightarrow$ 5 $\rightarrow$ 3).

---

### PHẦN 5: BA GIẢI PHÁP HỖ TRỢ HỌC TẬP CỤ THỂ

1. **Tổ chức buổi trao đổi 1-1 với nhóm sinh viên sa sút liên tục:** Giảng viên cần hẹn gặp riêng An, Bình và Dũng để xem xét lại bài kiểm tra các tuần qua, khoanh vùng các nội dung kiến thức ở Tuần 2 và Tuần 3 mà nhóm này bị mất điểm.
2. **Thiết lập cơ chế kiểm tra và đánh giá sớm:** Chia nhỏ các bài kiểm tra hoặc bài tập thực hành ngắn sau mỗi buổi học thay vì dồn dồn qua từng tuần để phát hiện kịp thời sự sụt giảm điểm số của sinh viên (như trường hợp của Hà hay Chi ở tuần cuối).
3. **Thành lập nhóm học tập hỗ trợ (Peer Tutoring):** Ghép nối sinh viên có kết quả ổn định cao (như Chi, Hà) cùng tham gia hỗ trợ ôn tập cho các sinh viên có điểm số thấp hoặc giảm sâu (như Dũng, Bình, An) trong các bài tập thực hành lập trình.

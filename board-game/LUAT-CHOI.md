# THIÊN HẠ PHÂN TRANH
### Board game chiến thuật phong cách Total War — bản prototype v0.1

| | |
|---|---|
| Số người chơi | 2 – 4 |
| Thời gian | 90 – 150 phút (bản nhanh 2 người: ~60 phút) |
| Độ tuổi | 12+ |
| Thể loại | Chiếm lãnh thổ + trận đánh chiến thuật trên bàn trận riêng |

**Ý tưởng cốt lõi:** giữ đúng cấu trúc hai lớp của Total War. Lớp **chiến dịch** là bản đồ tỉnh thành theo lượt (thu thuế, tuyển quân, hành quân, ngoại giao). Khi hai quân đội chạm nhau, chuyển sang lớp **trận đánh**: hai bên bí mật dàn quân lên bàn trận 3 cột × 2 hàng, rồi đánh theo pha bắn tên, xung phong, giáp lá cà và kiểm tra tinh thần. Thắng trận nhờ dàn quân đúng và đánh sườn, không phải nhờ đông quân.

---

## 1. Thành phần

### 1.1 Bản đồ chiến dịch
- 1 bản đồ **20 tỉnh** (dùng 12 tỉnh khi chơi 2 người, 16 tỉnh khi 3 người).
- Mỗi tỉnh ghi: **địa hình** (Đồng bằng / Rừng / Đồi / Sông), **thuế** (1 – 3 vàng), và có hoặc không có **Thành**.
- Mỗi người chơi có 1 **Kinh đô** (tỉnh có Thành, thuế 3) ở góc bản đồ.

### 1.2 Quân (mỗi người chơi, một màu)
| Loại | Ký hiệu | Số lượng | Giá tuyển | Vai trò |
|---|---|---|---|---|
| Bộ binh | ■ | 12 | 2 vàng | Giữ hàng trước, chịu xung phong |
| Cung thủ | ▲ | 8 | 3 vàng | Bắn từ hàng sau, yếu khi bị áp sát |
| Kỵ binh | ● | 6 | 4 vàng | Xung phong vào cột trống, truy kích |
| Tướng | ★ | 2 | 6 vàng | Tăng tinh thần, cho đổ lại xúc xắc |

Quân chưa tuyển để trong **kho dự trữ** của người chơi.

### 1.3 Thành phần khác
- 2 **bàn trận** (một cho mỗi bên khi đánh), mỗi bàn 3 cột × 2 hàng.
- 2 **tấm chắn** để dàn quân bí mật.
- 40 **thẻ Chiến thuật**, 20 **thẻ Sự kiện**.
- Token **Thành** (10), token **Hiệp ước** (8), vàng (đồng xu hoặc cube).
- 12 xúc xắc 6 mặt.
- Bảng theo dõi vòng (8 vòng).

---

## 2. Chuẩn bị
1. Mỗi người chọn phe, đặt **Kinh đô**, nhận **5 vàng**, đặt lên Kinh đô: 4 Bộ binh, 2 Cung thủ, 1 Kỵ binh, 1 Tướng.
2. Các tỉnh trung lập còn lại đặt **quân trung lập**: 2 Bộ binh (tỉnh thuế 1), 3 Bộ binh + 1 Cung thủ (thuế 2), 4 Bộ binh + 2 Cung thủ (thuế 3, có Thành).
3. Xáo hai bộ thẻ. Mỗi người rút 2 thẻ Chiến thuật.
4. Người ít tuổi nhất đi trước, sau đó theo chiều kim đồng hồ.

---

## 3. Vòng chiến dịch

Trò chơi kéo dài tối đa **8 vòng**. Mỗi vòng có 4 giai đoạn, làm theo thứ tự.

### 3.1 Sự kiện
Lật 1 thẻ Sự kiện, áp dụng cho tất cả (ví dụ: *Mất mùa*: tỉnh Đồng bằng thuế −1 vòng này; *Dịch bệnh*: quân đội có trên 8 quân mất 1 Bộ binh; *Mùa khô*: Sông không cản trở).

### 3.2 Thu nhập
Mỗi người nhận vàng = tổng thuế các tỉnh mình kiểm soát, **+1 cho mỗi Thành**.
**Lương quân:** mỗi quân đội đóng **ngoài lãnh thổ của mình** tốn 1 vàng. Không trả được thì bỏ 1 quân trong quân đội đó.

### 3.3 Hành động (lần lượt từng người, 3 điểm hành động mỗi người)
Mỗi điểm hành động chọn một trong các việc sau. Có thể làm cùng một việc nhiều lần.

| Hành động | Hiệu quả |
|---|---|
| **Tuyển quân** | Trả vàng, đặt tối đa 4 quân từ kho vào **một tỉnh có Thành** của mình. |
| **Hành quân** | Di chuyển một quân đội (toàn bộ hoặc một phần quân trong tỉnh) sang **1 tỉnh kề**. Quân đội chỉ gồm Kỵ binh (và Tướng) đi được **2 tỉnh**. Vào tỉnh có quân khác → **trận đánh** ở giai đoạn 3.4. |
| **Xây Thành** | Trả 5 vàng, đặt token Thành vào một tỉnh mình kiểm soát (tối đa 1 Thành mỗi tỉnh). |
| **Ngoại giao** | Đưa 1 token Hiệp ước cho một người chơi khác. Nếu họ nhận, hai bên **không được tấn công nhau trong vòng này và vòng sau**. Phá hiệp ước: mất 3 vàng cho đối phương và mọi quân đội của kẻ phá bị −1 tinh thần đến hết ván. |
| **Mưu kế** | Rút 1 thẻ Chiến thuật (tối đa 4 thẻ trên tay). |

**Kiểm soát tỉnh:** tỉnh thuộc về người có quân ở đó. Tỉnh không có quân vẫn thuộc chủ cũ cho đến khi có người khác hành quân vào.

### 3.4 Giải quyết trận đánh
Mọi tỉnh có quân của hai bên trở lên được giải quyết theo thứ tự người đi lượt. Xem **mục 4**. Ba bên trở lên trong một tỉnh: người đến sau đánh người đang giữ tỉnh trước, người thắng đánh tiếp.

### 3.5 Kết thúc vòng
Đẩy marker vòng. Kiểm tra điều kiện chiến thắng (mục 6).

---

## 4. Trận đánh (trái tim của trò chơi)

### 4.1 Bàn trận
Mỗi bên có bàn trận riêng, hai bàn đặt đối diện nhau:

```
         BÊN PHÒNG THỦ
   Hậu quân  [ T ] [ G ] [ P ]
   Tiền quân [ T ] [ G ] [ P ]
   ─────────────────────────────
   Tiền quân [ T ] [ G ] [ P ]
   Hậu quân  [ T ] [ G ] [ P ]
         BÊN TẤN CÔNG
   T = cánh Trái, G = Giữa, P = cánh Phải
```
Cột **Trái** của bên này đối diện cột **Phải** của bên kia. Mỗi ô chứa **tối đa 3 quân**, vậy mỗi bên dàn tối đa **18 quân**; quân dư để ở **hậu bị** và chỉ vào thay khi có ô trống ở cuối vòng trận.

### 4.2 Dàn quân bí mật
Hai bên dựng tấm chắn, dàn quân đồng thời, rồi hạ chắn cùng lúc. Đây là lúc đoán ý đối thủ: dồn quân một cánh để đánh sườn, hay dàn đều để giữ.

**Địa hình tỉnh** (áp dụng cả trận):
- **Rừng:** Kỵ binh không được xung phong. Thẻ *Phục kích* dùng được.
- **Đồi:** Cung thủ bên phòng thủ trúng với **4+** thay vì 5+.
- **Sông:** Vòng trận đầu, bên tấn công **không đánh giáp lá cà** (đang lội sông).
- **Thành:** Bên phòng thủ bỏ qua **2 hit đầu tiên** mỗi vòng trận. Bên tấn công phải thắng để chiếm; nếu không thắng sau 4 vòng, rút lui.

### 4.3 Vòng trận
Một trận có tối đa **4 vòng trận**. Mỗi vòng theo thứ tự 5 pha. Trong mỗi pha, hai bên đổ xúc xắc **đồng thời**, hit được tính xong rồi mới gỡ quân.

**Pha 0 – Chiến thuật:** mỗi bên có thể lật úp 1 thẻ Chiến thuật, lật ngửa cùng lúc, áp dụng ngay.

**Pha 1 – Mưa tên.** Mỗi **Cung thủ ở Hậu quân** đổ 1 xúc xắc, trúng khi **5+**. Mỗi hit gỡ 1 quân đối phương ở **Tiền quân cột đối diện**; nếu cột ấy trống thì gỡ ở Hậu quân cột đối diện; nếu cả cột trống thì chọn bất kỳ. Cung thủ ở Tiền quân không bắn, chỉ đánh giáp lá cà như Bộ binh nhưng trúng **6**.

**Pha 2 – Xung phong.** Mỗi **Kỵ binh ở Tiền quân** đổ 1 xúc xắc:
- Cột đối diện **không có Bộ binh ở Tiền quân** → trúng khi **3+**.
- Có Bộ binh ở Tiền quân → trúng khi **5+**.
- Gỡ quân ở Tiền quân cột đối diện trước, rồi Hậu quân.

**Pha 3 – Giáp lá cà.** Mỗi **Bộ binh ở Tiền quân** đổ 1 xúc xắc, trúng khi **4+**, gỡ quân Tiền quân cột đối diện (rồi Hậu quân). Tướng ở Tiền quân cũng đánh, trúng **4+**.

**Pha 4 – Đánh sườn.** Nếu **cả cột đối diện trống** (Tiền và Hậu), mọi quân của bạn ở cột ấy được **tấn công sang cột kề bên** của đối phương ngay trong pha này, mỗi quân đổ 1 xúc xắc trúng **3+** (bất kể loại). Đây là phần thưởng cho việc đánh sập một cánh.

**Pha 5 – Tinh thần.** Mỗi bên tính số quân **đã mất trong vòng trận này**. Bên mất nhiều hơn phải **kiểm tra tinh thần**: đổ 1 xúc xắc, **cộng 1 nếu còn Tướng trên bàn trận**, cộng 1 nếu đang phòng thủ trong Thành. Nếu kết quả **≤ số quân mất vòng này** → **tan rã** (xem 4.5). Hai bên mất bằng nhau: không ai kiểm tra.

**Cuối vòng trận:** bổ sung quân từ hậu bị vào ô trống, mỗi ô 1 quân. Quân đã ở bàn trận **không đổi ô** (trừ khi thẻ cho phép). Rồi sang vòng trận mới.

### 4.4 Tướng
- Mỗi vòng trận, bên có Tướng được **đổ lại 1 xúc xắc** bất kỳ.
- Tướng chỉ bị gỡ khi là **quân cuối cùng** trong ô đó. Khi Tướng bị gỡ, bên ấy kiểm tra tinh thần **ngay lập tức** với −1.
- Tướng chết thì về kho, phải tuyển lại.

### 4.5 Kết thúc trận
Trận kết thúc khi một bên **tan rã**, một bên **hết quân trên bàn trận và hậu bị**, hoặc **hết 4 vòng trận**.
- **Bên tan rã** rút toàn bộ quân về **tỉnh kề gần nhất do mình kiểm soát**. Trước khi rút, bên thắng **truy kích**: mỗi Kỵ binh còn sống của bên thắng gỡ thêm 1 quân bên thua (tối đa 3). Không có tỉnh để rút → mất toàn bộ.
- **Hết 4 vòng mà không ai tan rã:** bên tấn công rút lui (không bị truy kích). Bên phòng thủ giữ tỉnh.
- Bên thắng nhận **1 điểm Chiến công** và rút 1 thẻ Chiến thuật. Chiếm được tỉnh có Thành: cướp **3 vàng** của chủ cũ.

### 4.6 Tự giải (khi muốn chơi nhanh)
Mỗi bên đổ số xúc xắc = số quân chia 2 (làm tròn lên), **+1 xúc xắc nếu có Tướng**, +1 nếu phòng thủ trong Thành. Mỗi kết quả 4+ là 1 hit. Bên ít hit hơn thua và mất quân bằng số hit đối phương; bên thắng mất quân bằng nửa số hit đối phương (làm tròn xuống). Hòa thì bên tấn công rút lui. Dùng tự giải cho trận đánh quân trung lập để tiết kiệm thời gian.

---

## 5. Thẻ Chiến thuật (40 thẻ, mỗi loại 4 thẻ)

| Thẻ | Hiệu lực (dùng ở Pha 0, một thẻ mỗi vòng trận) |
|---|---|
| **Phục kích** | Chỉ ở tỉnh Rừng. Pha 3 của bạn diễn ra **trước** pha 1 của đối phương vòng này. |
| **Mưa tên dày đặc** | Cung thủ Hậu quân của bạn trúng **4+** vòng này. |
| **Thiết kỵ xung phong** | Kỵ binh xung phong trúng **4+** dù có Bộ binh đối diện. |
| **Trận địa cự mã** | Kỵ binh đối phương không được xung phong vòng này. |
| **Giả lui** | Cuối vòng này, bạn được **đổi chỗ 2 ô** bất kỳ trên bàn trận của mình. |
| **Hỏa công** | Gỡ 1 quân đối phương ở ô bất kỳ trước pha 1. Không dùng được khi trời mưa (thẻ Sự kiện). |
| **Khích lệ** | Bỏ qua kiểm tra tinh thần vòng này. |
| **Nghi binh** | Sau khi hạ tấm chắn, bạn được **đổi chỗ 1 ô** của mình trước khi vào vòng trận 1. Chỉ dùng được vòng 1. |
| **Chém tướng** | Pha 1: nếu bạn có Cung thủ bắn trúng ô có Tướng đối phương, gỡ Tướng ngay dù ô còn quân khác. |
| **Tiếp viện** | Đưa **tối đa 3 quân** từ một tỉnh kề do bạn kiểm soát vào hậu bị ngay. |

---

## 6. Chiến thắng
Thắng **ngay lập tức** khi đạt một trong hai:
- Kiểm soát **8 tỉnh** (4 người) / **7 tỉnh** (3 người) / **7 tỉnh trong 12** (2 người).
- Chiếm **Kinh đô** của một đối thủ và giữ được đến hết vòng kế tiếp.

Nếu hết **vòng 8** mà chưa ai thắng, tính điểm:
- 1 điểm mỗi tỉnh, +2 mỗi Thành, +1 mỗi điểm Chiến công, +1 mỗi 5 vàng còn lại.

---

## 7. Biến thể
- **Bản nhanh 2 người (60 phút):** bản đồ 12 tỉnh, 6 vòng, mỗi người 2 điểm hành động, trận đánh tối đa 3 vòng trận.
- **Chế độ chiến dịch dài:** 12 vòng, thêm luật **Công nghệ**: trả 6 vàng để nâng vĩnh viễn 1 trong 3: Cung thủ trúng 4+ / Bộ binh bỏ qua 1 hit mỗi vòng trận / Kỵ binh đi 3 tỉnh.
- **Chơi một người (giả lập AI):** quân trung lập và phe đối thủ hành động theo luật: luôn tấn công tỉnh kề yếu nhất nếu có ưu thế ≥ 1,5 lần quân, ngược lại tuyển quân rồi dồn về biên giới.

---

## 8. Hướng dẫn in và thử nghiệm (print-and-play)
1. **Bản đồ:** vẽ 20 ô lục giác hoặc vùng tự do trên giấy A3, tô màu địa hình, ghi thuế. Gợi ý phân bổ: 8 Đồng bằng, 5 Rừng, 4 Đồi, 3 Sông; 4 Kinh đô + 4 Thành trung lập.
2. **Quân:** dùng cube gỗ 4 màu (■ Bộ binh), meeple nhỏ (▲ Cung thủ), đĩa (● Kỵ binh), meeple lớn (★ Tướng). Hoặc in token tròn 2 cm.
3. **Bàn trận:** in 2 bàn 3×2 trên giấy A4, mỗi ô 6×6 cm.
4. **Thẻ:** in 60 thẻ cỡ poker, dán lên thẻ bài cũ.
5. **Thứ tự thử nghiệm đề xuất:** chơi 2 người, chỉ dùng luật trận đánh (mục 4) với hai đội 12 quân cố định 3 trận để cảm nhận cân bằng, rồi mới chơi cả chiến dịch.

### Những điểm cần quan sát khi test
- Kỵ binh có quá mạnh khi đối thủ dàn ít Bộ binh không? (Nếu có: xung phong vào cột trống trúng 4+ thay cho 3+.)
- Trận có kết thúc trước vòng 4 đủ thường xuyên không? (Nếu không: tinh thần kiểm tra khi kết quả ≤ số quân mất **+1**.)
- Thu nhập 3 điểm hành động có khiến người đi trước lợi quá không? (Nếu có: xoay người đi đầu mỗi vòng.)

---

## 9. Demo điện tử
`board-game/demo-tran-danh.html` là bản mô phỏng phần trận đánh (mục 4) chạy ngay trên trình duyệt, không cần cài gì: mở file, chọn vai và địa hình, dàn quân rồi đánh với máy. Dùng nó để test cân bằng trước khi in bàn trận.

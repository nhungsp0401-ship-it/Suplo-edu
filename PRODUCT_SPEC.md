# Suplo Edu — Tài liệu Đặc tả Sản phẩm

> App tạo tài liệu học tập cá nhân hóa cho trẻ 3,5–6 tuổi,  
> định hướng thi đầu vào lớp 1 tại các trường trọng điểm Hà Nội.

---

## Mục lục

1. [Tổng quan sản phẩm](#1-tổng-quan-sản-phẩm)
2. [Trường mục tiêu & yêu cầu tuyển sinh](#2-trường-mục-tiêu--yêu-cầu-tuyển-sinh)
3. [Lộ trình học theo giai đoạn](#3-lộ-trình-học-theo-giai-đoạn)
4. [Nội dung từng môn học](#4-nội-dung-từng-môn-học)
5. [Tính năng tương tác](#5-tính-năng-tương-tác)
6. [Phương pháp sư phạm](#6-phương-pháp-sư-phạm)
7. [Cấu trúc một bài học](#7-cấu-trúc-một-bài-học)
8. [Hệ thống đánh giá & báo cáo](#8-hệ-thống-đánh-giá--báo-cáo)
9. [Bộ sinh tài liệu (Document Generator)](#9-bộ-sinh-tài-liệu-document-generator)
10. [Đặc tả kỹ thuật](#10-đặc-tả-kỹ-thuật)
11. [Lộ trình phát triển sản phẩm](#11-lộ-trình-phát-triển-sản-phẩm)

---

## 1. Tổng quan sản phẩm

### 1.1 Tầm nhìn

**Suplo Edu** là nền tảng sinh tài liệu học tập thích ứng (adaptive learning document generator) dành riêng cho trẻ từ **3,5 đến 6 tuổi**, giúp phụ huynh và giáo viên tạo ra các bộ bài tập được cá nhân hóa theo:

- Độ tuổi và mức độ phát triển nhận thức hiện tại của trẻ
- Mục tiêu trường đầu vào (Nguyễn Siêu, Ngôi Sao Cầu Giấy, Đoàn Thị Điểm…)
- Điểm mạnh/yếu của từng trẻ qua dữ liệu làm bài

### 1.2 Vấn đề giải quyết

| Vấn đề của phụ huynh | Giải pháp Suplo Edu |
|---|---|
| Không biết con cần học gì để thi vào trường A | Lộ trình cụ thể theo từng trường mục tiêu |
| Bài tập tìm trên mạng không phù hợp độ tuổi | Bài tập được sinh ra khớp với mức phát triển nhận thức của trẻ |
| Con nhanh chán, không chịu ngồi học | Gamification, mini-game, nhân vật dẫn dắt |
| Khó biết con đang ở đâu trong lộ trình | Dashboard tiến độ trực quan cho phụ huynh |
| Tốn thời gian in ấn, sắp xếp tài liệu | Xuất PDF/printable worksheets chỉ với 1 click |

### 1.3 Đối tượng người dùng

**Người dùng chính (primary):** Phụ huynh có con 3,5–6 tuổi tại Hà Nội, muốn chuẩn bị cho con thi vào lớp 1 trường trọng điểm.

**Người dùng phụ (secondary):** Giáo viên mầm non, trung tâm luyện thi tiền tiểu học.

---

## 2. Trường mục tiêu & yêu cầu tuyển sinh

### 2.1 Trường Tiểu học Nguyễn Siêu

**Hình thức tuyển sinh:** "Một ngày em là học sinh lớp 1" — đánh giá năng lực qua trải nghiệm thực tế, không thi viết căng thẳng.

| Phần thi | Nội dung cụ thể | Trọng số |
|---|---|---|
| **IQ & Tư duy** | Thêm bớt số trong phạm vi 10; tìm quy luật hình (dãy lặp, quy luật tăng/giảm) | Cao |
| **Tiếng Việt** | Nghe câu chuyện ngắn, trả lời câu hỏi trắc nghiệm A/B/C/D; kể chuyện qua tranh | Trung bình |
| **Tiếng Anh** | Theo nhóm 4 bạn; làm bài tập theo chỉ dẫn của giáo viên nước ngoài; phỏng vấn ngắn | **Rất cao** |
| **Kỹ năng mềm** | Tự phục vụ, làm việc nhóm, tự tin giao tiếp | Trung bình |

> **Lưu ý quan trọng:** Tiếng Anh là yếu tố **then chốt** để đỗ Nguyễn Siêu. Trẻ cần có khả năng nghe hiểu và phản hồi chỉ dẫn bằng tiếng Anh từ người nước ngoài.

### 2.2 Trường Tiểu học Đoàn Thị Điểm

**Hình thức tuyển sinh:** Đánh giá năng lực qua 3 phần độc lập.

| Phần thi | Nội dung cụ thể | Ghi chú |
|---|---|---|
| **Trắc nghiệm IQ** | Quan sát tìm điểm khác biệt; sắp xếp hình theo quy luật; bài tập logic không dùng số | Bút chì, tô màu |
| **Kể chuyện** | Giáo viên đưa 3 tranh, trẻ kể thành câu chuyện có đầu-cuối | Kiểm tra ngôn ngữ, tư duy |
| **Tiếng Anh** | Nghe từ/câu và nhắc lại; kiểm tra phát âm, trí nhớ thính giác | Không yêu cầu đọc/viết |

**Yêu cầu sức khỏe:** Loại A, cân nặng ≥ 19kg, không bệnh mãn tính.

### 2.3 Trường Ngôi Sao Cầu Giấy

**Chỉ tiêu:** 9 lớp × 32 học sinh/lớp, cạnh tranh cao.

| Phần đánh giá | Nội dung |
|---|---|
| **Toán cơ bản** | Đếm số 1–20, nhận dạng hình khối, so sánh nhiều/ít/bằng |
| **Tư duy không gian** | Ghép hình, xếp khối, hoàn thành hình còn thiếu |
| **Giao tiếp tiếng Việt** | Nói câu hoàn chỉnh, trả lời câu hỏi mạch lạc |
| **Tiếng Anh cơ bản** | Từ vựng chủ đề quen thuộc (màu sắc, con số, gia đình, đồ vật) |

### 2.4 Ma trận kỹ năng cần thiết cho tất cả các trường

```
                    Nguyễn Siêu   Đoàn Thị Điểm   Ngôi Sao
Toán cơ bản             ●●●           ●●●             ●●●
Tư duy logic            ●●●           ●●●             ●●●
Tiếng Anh               ●●●           ●●○             ●●○
Tiếng Việt              ●●○           ●●●             ●●○
Kỹ năng xã hội          ●●●           ●●○             ●●○
Tư duy không gian       ●●○           ●●●             ●●●

● = Cần thiết   ○ = Có thêm điểm cộng
```

---

## 3. Lộ trình học theo giai đoạn

### Tổng quan lộ trình (3,5 tuổi → 6 tuổi)

```
GĐ 1          GĐ 2          GĐ 3          GĐ 4
3,5–4,5T      4,5–5,5T      5,5–6T        6T (ôn thi)
Nền tảng  →  Phát triển  →  Nâng cao  →  Luyện đề
```

---

### Giai đoạn 1: Nền tảng nhận thức (3,5 – 4,5 tuổi)

**Mục tiêu:** Xây dựng "vốn" tư duy cốt lõi — quan sát, so sánh, phân loại, ghi nhớ.

**Thời lượng khuyến nghị:** 10 phút/ngày, 5 ngày/tuần

| Môn | Nội dung học | Kỹ năng đích |
|---|---|---|
| **Toán** | Đếm 1–10; nhận dạng hình (tròn, vuông, tam giác, chữ nhật); phân biệt kích thước (to/nhỏ, dài/ngắn, nhiều/ít) | Nền tảng số học, tư duy không gian |
| **Tiếng Việt** | Phân biệt âm thanh trong tiếng Việt; nhận dạng chữ cái; từ vựng chủ đề (gia đình, đồ vật, màu sắc, con vật) | Phát triển ngôn ngữ, tiền đọc viết |
| **Tiếng Anh** | Chào hỏi cơ bản; số 1–10; màu sắc; con vật; bài hát và rhyme | Làm quen âm vị tiếng Anh |
| **Tư duy** | Ghép đôi (match) hình-hình/hình-màu; sắp xếp theo thứ tự kích thước; tìm hình không cùng nhóm | Phân loại, nhận dạng quy luật đơn giản |

**Milestone cuối giai đoạn:**
- Đếm chính xác đến 10 và chỉ đúng số lượng đồ vật
- Nhận dạng tên 4 hình cơ bản
- Nói câu 3–5 từ mạch lạc bằng tiếng Việt
- Phản ứng với 5 lệnh tiếng Anh đơn giản (sit down, stand up, clap…)

---

### Giai đoạn 2: Phát triển tư duy (4,5 – 5,5 tuổi)

**Mục tiêu:** Hình thành tư duy logic — tìm quy luật, suy luận, giải quyết vấn đề đơn giản.

**Thời lượng khuyến nghị:** 15 phút/ngày, 5 ngày/tuần

| Môn | Nội dung học | Kỹ năng đích |
|---|---|---|
| **Toán** | Đếm và viết số 1–20; phép cộng/trừ trong phạm vi 5; so sánh số; nhận dạng đồng tiền; đo lường bằng vật thể | Số học ứng dụng |
| **Tiếng Việt** | Bảng chữ cái đầy đủ (đọc, nhận dạng, phát âm); từ ghép 2 âm tiết; kể chuyện qua tranh (3–4 tranh); câu hỏi-trả lời | Tiền đọc viết, kể chuyện |
| **Tiếng Anh** | Số 1–20; gia đình; trường học; cơ thể; thực phẩm; câu hỏi "What is this?", "How many?"; bài hát chủ đề | Từ vựng theo chủ đề, hội thoại đơn giản |
| **Tư duy** | Tìm quy luật trong dãy hình (AB, ABC, ABBC…); hoàn thành ma trận 2×2; câu đố so sánh; bài tập nhân quả đơn giản | Tư duy quy nạp, suy diễn |

**Milestone cuối giai đoạn:**
- Làm đúng phép cộng/trừ trong phạm vi 5 không cần đồ vật hỗ trợ
- Đọc được tên 20 chữ cái tiếng Việt
- Kể lại câu chuyện 3 tranh có trình tự đầu-giữa-cuối
- Giao tiếp 2–3 lượt bằng tiếng Anh về chủ đề quen thuộc

---

### Giai đoạn 3: Nâng cao & Tích hợp (5,5 – 6 tuổi)

**Mục tiêu:** Hợp nhất kiến thức, nâng độ khó tiệm cận với format thi thực tế.

**Thời lượng khuyến nghị:** 20 phút/ngày, 5 ngày/tuần

| Môn | Nội dung học | Kỹ năng đích |
|---|---|---|
| **Toán** | Phép cộng/trừ phạm vi 10; nhận dạng số thứ tự; bài toán có lời (ghép hình minh họa); tách số; hình học 2D–3D | Tư duy toán học ứng dụng |
| **Tiếng Việt** | Ghép vần đơn giản (âm + vần = tiếng); hiểu câu hỏi phức tạp hơn; kể chuyện từ 5+ tranh; điền từ vào chỗ trống | Sẵn sàng học đọc |
| **Tiếng Anh** | Giới thiệu bản thân đầy đủ; mô tả đồ vật (màu, hình, kích thước); câu hỏi "Where is…?", "Can you…?"; follow 3-step instruction | Giao tiếp thực hành |
| **Tư duy** | Ma trận 3×3; dãy số có quy luật (+1, +2, ×2); bài toán logic 2 bước; ghép bóng với hình; phân loại theo nhiều thuộc tính | Tư duy logic nâng cao |

---

### Giai đoạn 4: Ôn luyện thi đầu vào (6 tuổi — 3 tháng trước thi)

**Mục tiêu:** Làm quen với format đề thi thực tế, xây dựng tâm lý tự tin.

**Thời lượng:** 20–25 phút/ngày, 6 ngày/tuần

| Tuần | Nội dung |
|---|---|
| Tuần 1–2 | Mock test format Đoàn Thị Điểm (IQ + kể chuyện + tiếng Anh nghe nhắc lại) |
| Tuần 3–4 | Mock test format Nguyễn Siêu (tư duy + tiếng Anh phỏng vấn + kỹ năng nhóm) |
| Tuần 5–6 | Mock test format Ngôi Sao (toán + nhận dạng hình + giao tiếp) |
| Tuần 7–8 | Đề tổng hợp luân phiên, tập trung vào điểm yếu của từng trẻ |
| Tuần 9–10 | Giảm áp lực, chỉ ôn nhẹ; tập trung kỹ năng tự tin, tự lập, giao tiếp |
| Tuần 11–12 | Nghỉ ngơi, chơi tự do; chỉ duy trì 5–10 phút/ngày |

---

## 4. Nội dung từng môn học

### 4.1 Toán học

#### Phạm vi kiến thức

```
Level 1 (3,5–4,5T)    Level 2 (4,5–5,5T)    Level 3 (5,5–6T)
─────────────────     ─────────────────     ─────────────────
Đếm 1–10             Đếm 1–20             Cộng/trừ trong 10
Hình cơ bản          Cộng/trừ trong 5     Số thứ tự
Lớn/nhỏ/bằng        So sánh 2 số         Bài toán có lời
Nhiều/ít             Ghép số = tổng       Hình học 2D/3D
Phân loại            Nhận dạng đồng xu    Tách số / ghép số
```

#### Dạng bài tập toán

| Dạng bài | Mô tả | Giai đoạn |
|---|---|---|
| **Đếm và chỉ số** | Đếm đồ vật trong tranh, chỉ vào con số tương ứng | GĐ1 |
| **So sánh trực quan** | Nhóm nào nhiều hơn? Cái nào to hơn? | GĐ1 |
| **Điền số còn thiếu** | _ 3 _ 5 _ 7 → điền 2, 4, 6 | GĐ1–2 |
| **Phép cộng tranh** | 2 quả táo + 3 quả táo = ? (có hình minh họa) | GĐ2 |
| **Phép trừ tranh** | 5 con chim, bay đi 2 con, còn lại mấy con? | GĐ2 |
| **Tìm số bị ẩn** | 3 + ? = 7 | GĐ2–3 |
| **Bài toán có lời** | "Lan có 4 cái kẹo, mẹ cho thêm 3 cái. Lan có tất cả mấy cái kẹo?" | GĐ3 |
| **Hình học** | Nhận dạng, đếm cạnh, ghép hình tạo hình mới | GĐ2–3 |

---

### 4.2 Tiếng Anh

#### Phạm vi từ vựng (theo chủ đề)

| Chủ đề | Level 1 (10–15 từ) | Level 2 (20–30 từ) | Level 3 (40–50 từ) |
|---|---|---|---|
| Numbers | 1–10 | 1–20 | Ordinals (1st–10th) |
| Colors | 6 màu cơ bản | 12 màu | Mô tả màu sắc đồ vật |
| Family | Mom, dad, baby | Grandparents, siblings | Possessives (my, your) |
| Animals | 10 con vật quen | 20 con vật + habitat | Verbs (fly, swim, run) |
| Shapes | Circle, square, triangle | Rectangle, star, heart | 3D: cube, sphere |
| Food | 10 món phổ biến | 20 món | Like/don't like |
| School | Bag, book, pencil | Classroom objects | School activities |
| Body | Head, hands, feet | 10 bộ phận | Actions (jump, clap) |

#### Cấu trúc câu theo cấp độ

```
Level 1: "A cat."  /  "Red ball."  /  "Hello!"
Level 2: "This is a cat."  /  "I see a red ball."  /  "How are you?"
Level 3: "The cat is on the mat."  /  "I have two red balls."
         "Can you help me?"  /  "My name is Minh. I am 5 years old."
```

#### Kỹ năng ưu tiên (theo yêu cầu Nguyễn Siêu)

1. **Listening comprehension** — hiểu và thực hiện lệnh 1–3 bước bằng tiếng Anh
2. **Oral response** — trả lời câu hỏi có/không, one-word, short phrase
3. **Pronunciation** — phát âm chuẩn 26 chữ cái, vowel sounds cơ bản
4. **Confidence** — tự tin giao tiếp với người nước ngoài, không e ngại

---

### 4.3 Tiếng Việt

#### Phạm vi kiến thức

| Kỹ năng | Level 1 | Level 2 | Level 3 |
|---|---|---|---|
| **Nghe hiểu** | Câu đơn, lệnh 1 bước | Câu phức, câu hỏi | Đoạn ngắn, câu chuyện |
| **Nói** | Câu 3–5 từ | Câu hoàn chỉnh, kể sự việc | Kể chuyện mạch lạc 3–5 câu |
| **Chữ cái** | Nhận dạng 10 chữ | Toàn bộ bảng chữ cái | Phân biệt âm đầu, ghép vần |
| **Từ vựng** | 100 từ chủ đề quen thuộc | 200 từ | 350+ từ |

#### Dạng bài tiếng Việt

| Dạng bài | Mô tả | Gắn với kỹ năng thi |
|---|---|---|
| **Nhận dạng chữ cái** | Tô màu/khoanh tròn chữ cái được yêu cầu | Nhận mặt chữ |
| **Nối tranh-từ** | Kéo thả nối hình ảnh với từ tương ứng | Từ vựng |
| **Nghe và chọn** | Nghe audio, chọn tranh đúng trong 4 lựa chọn | Nghe hiểu |
| **Kể chuyện tranh** | Xem 3–5 tranh, kể lại câu chuyện có trình tự | Kỹ năng thi Đoàn Thị Điểm |
| **Trả lời câu hỏi** | Nghe câu chuyện, trả lời trắc nghiệm A/B/C/D | Kỹ năng thi Nguyễn Siêu |
| **Điền từ** | Điền từ còn thiếu vào câu có hình gợi ý | Tổng hợp |

---

### 4.4 Tư duy Logic

#### Hệ thống 5 nhóm kỹ năng tư duy

**Nhóm 1 — Quan sát & Phân biệt**
- Tìm điểm khác biệt giữa 2 tranh (4–7 điểm khác)
- Tìm hình "lạc loài" trong nhóm 4 hình
- Ghép bóng với hình

**Nhóm 2 — Phân loại & Nhóm**
- Phân loại theo 1 thuộc tính (màu, hình, kích thước)
- Phân loại theo 2 thuộc tính (màu + hình)
- Venn diagram đơn giản (cái gì thuộc cả 2 nhóm?)

**Nhóm 3 — Tìm quy luật (Pattern Recognition)**

```
Chuỗi đơn:     ○ □ ○ □ ○ ?          → □
Chuỗi 3 phần:  △ ○ □ △ ○ ?          → □
Quy luật màu:  🔴🔵🔴🔵🔴 ?          → 🔵
Số học:        1 2 3 4 5 ?          → 6
Số tăng 2:     2 4 6 8 ?            → 10
Ma trận 2×2:   hình học 4 ô, tìm ô trống
Ma trận 3×3:   nâng cao, format Đoàn Thị Điểm
```

**Nhóm 4 — Suy luận Nhân-Quả**
- "Tại sao bạn gấu khóc?" (xem tranh)
- "Bước tiếp theo là gì?" (chuỗi hành động)
- "Điều gì xảy ra nếu…?" (câu hỏi giả định đơn giản)

**Nhóm 5 — Không gian & Hình học**
- Xoay hình (hình này trông như thế nào nếu lật ngược?)
- Ghép mảnh (puzzle 4–9 mảnh)
- Đếm hình ẩn (có bao nhiêu tam giác trong hình?)

---

## 5. Tính năng tương tác

### 5.1 Giao diện học tập

**Nguyên tắc thiết kế UI/UX cho trẻ 3,5–6 tuổi:**
- Vùng tap/click tối thiểu **48×48 dp** (ngón tay trẻ lớn hơn người lớn)
- Màu sắc tươi sáng, tương phản cao, ít text, nhiều hình
- Âm thanh phản hồi tức thì cho mỗi tương tác
- Animation ngắn (< 1 giây) tránh làm trẻ mất tập trung
- Không có quảng cáo, pop-up gây xao nhãng

### 5.2 Các kiểu tương tác trong bài học

| Kiểu tương tác | Mô tả | Môn áp dụng |
|---|---|---|
| **Tap to select** | Chạm vào đáp án đúng | Tất cả |
| **Drag & Drop** | Kéo thả ghép đôi, xếp thứ tự | Toán, Tư duy |
| **Trace (tô theo đường)** | Tô theo nét chữ số, chữ cái | Toán, Tiếng Việt |
| **Mic input** | Nói câu trả lời, hệ thống nhận dạng giọng | Tiếng Anh, Tiếng Việt |
| **Pinch & Zoom** | Phóng to tranh tìm điểm khác biệt | Tư duy |
| **Sort/Order** | Kéo sắp xếp thứ tự | Tư duy, Toán |
| **Color fill** | Tô màu theo hướng dẫn | Tiếng Anh (colors), Tư duy |
| **Connect dots** | Nối đường từ điểm A đến điểm B | Chữ cái, Hình học |

### 5.3 Hệ thống Gamification

**Tiến trình nhân vật (Character Progression):**
- Trẻ có nhân vật đồng hành riêng (chọn từ 5 nhân vật: Sóc, Thỏ, Cá Vàng, Bướm, Chim Sẻ)
- Nhân vật "lớn lên" và có thêm accessories khi trẻ hoàn thành bài học
- Nhân vật phản ứng tích cực/buồn theo kết quả bài làm

**Hệ thống phần thưởng:**

```
Hoàn thành bài học     → +10 ngôi sao ⭐
Đúng lần đầu tiên     → Bonus +5 ngôi sao
Streak 5 ngày liên tiếp → Huy hiệu đặc biệt 🏅
Hoàn thành cả giai đoạn → Mở khóa mini-game mới 🎮
```

**Mini-games (phần thưởng sau khi học):**
- **Number Bubble Pop** — bắn bóng bay theo số đúng
- **Word Balloon** — nhận dạng chữ cái, từ tiếng Anh qua bóng
- **Shape Builder** — ghép các hình cơ bản tạo thành đồ vật
- **Story Creator** — sắp xếp tranh tạo câu chuyện ngắn
- **Memory Match** — lật thẻ ghép đôi từ vựng-hình ảnh

### 5.4 Điều chỉnh độ khó thích ứng (Adaptive Difficulty)

```
Trẻ làm đúng ≥ 80% bài → Tự động tăng level (+1)
Trẻ làm đúng 50–79%    → Giữ nguyên, thêm gợi ý
Trẻ làm đúng < 50%     → Giảm 1 level, đổi dạng bài trình bày
Sau 3 lần không làm được → Mở "Chế độ hỗ trợ": animation hướng dẫn từng bước
```

---

## 6. Phương pháp sư phạm

### 6.1 Nền tảng lý thuyết

**Montessori-inspired learning:**
- Trẻ chủ động khám phá, không bị áp đặt
- Vật liệu học tập cụ thể trước khi trừu tượng (hình ảnh → số)
- Tự sửa lỗi — hệ thống hiển thị đúng/sai sau mỗi lần thử, không phán xét
- Tôn trọng nhịp độ học riêng của từng trẻ

**Zone of Proximal Development (Vygotsky):**
- Bài tập luôn ở mức "hơi thử thách" — không quá dễ (chán) cũng không quá khó (nản)
- Scaffolding: gợi ý giảm dần theo tiến trình

**Phương pháp học qua chơi (Play-based Learning):**
- Mọi bài tập được frame dưới dạng nhiệm vụ hoặc trò chơi
- Story-driven: mỗi tuần có câu chuyện chủ đề liên kết các môn học
- Kiến thức được áp dụng vào tình huống thực (mua sắm, nấu ăn, đếm đồ vật…)

### 6.2 Nguyên tắc thiết kế bài tập

1. **Cụ thể trước trừu tượng** — dùng hình ảnh/đồ vật trước khi dùng ký hiệu toán học
2. **Từ quen thuộc đến xa lạ** — chủ đề gần với cuộc sống trẻ (gia đình, thức ăn, đồ chơi)
3. **Lặp lại có chủ đích** — cùng 1 kỹ năng nhưng trình bày khác nhau
4. **Tích hợp liên môn** — bài toán đếm kết hợp tiếng Anh (count and say in English)
5. **Ghi nhận nỗ lực** — phần thưởng cho "cố gắng" không chỉ "đúng"

---

## 7. Cấu trúc một bài học

### 7.1 Template bài học chuẩn (15 phút)

```
┌─────────────────────────────────────────────────┐
│  WARM-UP (2 phút)                               │
│  Nhân vật dẫn dắt chào, nhắc lại bài hôm qua   │
│  "Hôm qua bạn Sóc học gì vậy? Nhớ lại nhé!"    │
├─────────────────────────────────────────────────┤
│  LEARN (5 phút)                                 │
│  Concept mới qua animation ngắn + ví dụ tương tác│
│  Trẻ tương tác 1–2 lần để verify hiểu           │
├─────────────────────────────────────────────────┤
│  PRACTICE (6 phút)                              │
│  5–8 bài tập áp dụng concept vừa học            │
│  Độ khó tăng dần trong phiên                    │
│  Gợi ý xuất hiện nếu trẻ làm sai lần 2         │
├─────────────────────────────────────────────────┤
│  REVIEW & REWARD (2 phút)                       │
│  Tóm tắt những gì đã học                        │
│  Trao phần thưởng, animation ăn mừng            │
│  Preview bài học tiếp theo                      │
└─────────────────────────────────────────────────┘
```

### 7.2 Các loại bài học đặc biệt

**Story Lesson (10 phút):**
Tuần 1 lần, kể câu chuyện ngắn tích hợp từ vựng 3 môn (toán, tiếng Anh, tiếng Việt). Trẻ tương tác với câu chuyện: chọn hành động của nhân vật, giải câu đố trong truyện.

**Challenge Day (20 phút, cuối tuần):**
Đề tổng hợp ngắn, format gần với thi thực tế. Không có gợi ý. Kết quả xuất ra report cho phụ huynh.

**Free Play (5 phút, tùy chọn):**
Mini-game không có áp lực đúng/sai, chỉ để vui. Trẻ có thể bỏ qua hoặc chơi lại nhiều lần.

---

## 8. Hệ thống đánh giá & báo cáo

### 8.1 Dashboard phụ huynh

**Theo dõi theo tuần:**
- Số ngày học / 7 ngày
- Tổng thời gian học
- % bài đúng theo từng môn
- Kỹ năng đã thành thạo (mastered) vs. đang học (in progress) vs. chưa học (not started)

**Biểu đồ tiến độ theo giai đoạn:**
```
Toán     ████████░░  80% hoàn thành giai đoạn 2
Tiếng Anh ██████░░░░  60%
Tiếng Việt ███████░░░  70%
Tư duy   █████░░░░░  50%
```

**Điểm mạnh & điểm cần chú ý:**
- Top 3 kỹ năng trẻ làm tốt nhất
- Top 3 kỹ năng cần luyện thêm + gợi ý bài tập bổ sung

### 8.2 Báo cáo Readiness trước khi thi

**3 tháng trước ngày thi dự kiến, app xuất báo cáo:**

```
ĐÁNH GIÁ SẴN SÀNG THI: TRƯỜNG NGUYỄN SIÊU
─────────────────────────────────────────────
Bé: Nguyễn Minh Anh | 5 tuổi 8 tháng
Ngày đánh giá: [date]

● Tiếng Anh:        78% ⚠️  Cần cải thiện
  └─ Nghe hiểu lệnh:  90% ✅
  └─ Phản xạ nói:     65% ⚠️  Luyện thêm speaking

● Tư duy logic:     85% ✅  Tốt
  └─ Tìm quy luật:   90% ✅
  └─ Ma trận:         80% ✅

● Toán cơ bản:      92% ✅  Xuất sắc

● Tiếng Việt:       88% ✅  Tốt

ĐỀ XUẤT: Tập trung 3 tuần tiếp theo vào Speaking tiếng Anh
[Xem kế hoạch chi tiết]  [Xuất PDF báo cáo]
```

---

## 9. Bộ sinh tài liệu (Document Generator)

### 9.1 Tính năng cốt lõi

**Input từ phụ huynh:**
1. Độ tuổi của trẻ (tháng)
2. Giai đoạn học hiện tại (hoặc để app tự đánh giá)
3. Trường mục tiêu (chọn 1–3 trường)
4. Điểm cần ưu tiên (môn học / kỹ năng)
5. Số lượng bài / tờ bài tập muốn in

**Output được tạo ra:**
- PDF worksheet có thể in 2 mặt, khổ A4
- Font chữ lớn, hình ảnh minh họa màu sắc
- Có tên trẻ và ngày tháng để dễ lưu trữ
- QR code liên kết đến bài tập tương tác tương ứng trên app

### 9.2 Các loại tài liệu có thể sinh

| Loại tài liệu | Mô tả | Số trang mặc định |
|---|---|---|
| **Daily Worksheet** | Bài tập 1 ngày, đa môn | 1 tờ (2 mặt) |
| **Weekly Pack** | Bài tập 5 ngày theo chủ đề tuần | 5 tờ |
| **Skill Booster** | Tập trung 1 kỹ năng cụ thể (VD: tìm quy luật) | 3 tờ |
| **Mock Exam** | Đề thi thử theo format trường cụ thể | 2–4 tờ |
| **Progress Poster** | Bảng theo dõi tiến độ treo tường (gamified) | 1 tờ A3 |
| **Vocabulary Cards** | Flashcard tiếng Anh in và cắt rời | 2 tờ / 20 thẻ |
| **Story + Exercise** | Câu chuyện ngắn kèm câu hỏi | 3 tờ |

### 9.3 Quy trình sinh tài liệu

```
Phụ huynh cấu hình
        ↓
AI Engine phân tích:
  - Mức độ hiện tại của trẻ (từ dữ liệu làm bài)
  - Yêu cầu của trường mục tiêu
  - Khoảng cách cần bù đắp
        ↓
Template engine điền nội dung:
  - Chọn bài tập từ ngân hàng (question bank)
  - Sắp xếp theo độ khó tăng dần
  - Chèn hình ảnh phù hợp
  - Thêm phần hướng dẫn cho phụ huynh (instructions box)
        ↓
Render PDF (< 10 giây)
        ↓
Preview → In / Lưu / Chia sẻ
```

### 9.4 Ngân hàng câu hỏi (Question Bank)

| Môn | Số lượng câu hỏi | Phân loại |
|---|---|---|
| Toán | 500+ | 8 dạng × 3 level × 20+ câu/dạng |
| Tiếng Anh | 400+ | 6 chủ đề × 4 kỹ năng × 15+ câu |
| Tiếng Việt | 350+ | 5 kỹ năng × 3 level × 20+ câu |
| Tư duy Logic | 600+ | 5 nhóm × 4 level × 30+ câu |
| **Tổng** | **1.850+** | |

---

## 10. Đặc tả kỹ thuật

### 10.1 Kiến trúc hệ thống

```
┌──────────────────────────────────────────────────────┐
│                    FRONTEND                          │
│  React Native (iOS + Android) / Next.js (Web)        │
│  - Lesson Player (interactive exercises)             │
│  - PDF Generator (client-side rendering)             │
│  - Parent Dashboard                                  │
└──────────────────┬───────────────────────────────────┘
                   │ REST API / GraphQL
┌──────────────────┴───────────────────────────────────┐
│                    BACKEND                           │
│  Node.js + Express / NestJS                          │
│  ┌─────────────────────────────────────────────┐    │
│  │  Adaptive Engine                            │    │
│  │  - Student progress model                  │    │
│  │  - Difficulty adjustment algorithm         │    │
│  │  - Content recommendation                  │    │
│  └─────────────────────────────────────────────┘    │
│  ┌─────────────────────────────────────────────┐    │
│  │  Document Generator                         │    │
│  │  - Template engine (Handlebars/Pug)         │    │
│  │  - PDF renderer (Puppeteer / PDFKit)        │    │
│  │  - Question Bank query engine              │    │
│  └─────────────────────────────────────────────┘    │
└──────────────────┬───────────────────────────────────┘
                   │
┌──────────────────┴───────────────────────────────────┐
│                    DATA LAYER                        │
│  PostgreSQL (user data, progress, question bank)     │
│  Redis (session, cache hot questions)                │
│  S3/CDN (images, audio, PDF output)                  │
│  Pinecone / pgvector (RAG for content matching)      │
└──────────────────────────────────────────────────────┘
```

### 10.2 AI/ML Components

| Component | Mô tả | Model/Approach |
|---|---|---|
| **Adaptive Difficulty** | Dự đoán câu hỏi phù hợp tiếp theo | Item Response Theory (IRT) + heuristic rules |
| **Speech Recognition** | Đánh giá phát âm tiếng Anh của trẻ | Whisper hoặc Google Speech-to-Text, custom accent model cho trẻ em VN |
| **Progress Prediction** | Dự báo ngày trẻ sẵn sàng thi | Logistic regression trên lịch sử làm bài |
| **Content Generation** | Sinh thêm bài tập mới khi cần | Claude API (few-shot prompting với template) |
| **Question Selection** | Chọn câu hỏi tối ưu từ question bank | Multi-armed bandit / greedy algorithm |

### 10.3 Hiệu năng & Yêu cầu

| Chỉ số | Yêu cầu |
|---|---|
| Thời gian sinh PDF | < 10 giây |
| Thời gian load bài học | < 2 giây |
| Uptime | 99.5% |
| Offline mode | Hỗ trợ học offline, sync khi có mạng |
| Thiết bị hỗ trợ | iOS 14+, Android 8+, Chrome/Safari trên tablet |
| Màn hình tối ưu | Tablet 7–10 inch (chính), smartphone 6+ inch (hỗ trợ) |

### 10.4 Bảo mật & Quyền riêng tư

- **COPPA compliant** — không thu thập dữ liệu cá nhân trẻ em trực tiếp
- Tài khoản tạo và quản lý bởi phụ huynh
- Không có social features giữa trẻ
- Dữ liệu học tập mã hóa at rest và in transit
- Phụ huynh có thể xóa toàn bộ dữ liệu bất cứ lúc nào

---

## 11. Lộ trình phát triển sản phẩm

### MVP (3 tháng đầu)

**Phạm vi:**
- [ ] Giai đoạn 1 & 2 cho môn Toán và Tư duy (phổ biến nhất, dễ ra nội dung)
- [ ] 100 bài học tương tác cơ bản
- [ ] Ngân hàng 400 câu hỏi
- [ ] Document Generator (sinh PDF worksheet cơ bản)
- [ ] Dashboard phụ huynh đơn giản (streak, % hoàn thành)
- [ ] Tài khoản phụ huynh + 1 hồ sơ trẻ

### V1.0 (6 tháng)

**Mở rộng:**
- [ ] Thêm môn Tiếng Việt và Tiếng Anh đầy đủ
- [ ] Giai đoạn 3 & 4 (nâng cao + ôn thi)
- [ ] Adaptive difficulty engine
- [ ] Mock exam cho 3 trường mục tiêu
- [ ] Readiness Report
- [ ] Voice input cho tiếng Anh

### V2.0 (12 tháng)

**Scale & Monetize:**
- [ ] Mở rộng thêm 5+ trường mục tiêu (FPT, BVIS, Archimedes…)
- [ ] AI content generation (tạo bài tập mới tự động)
- [ ] Teacher dashboard cho trung tâm luyện thi
- [ ] Parent community & tips sharing
- [ ] Subscription model tiers (Free / Plus / Premium)

---

## Phụ lục: Nguồn tham khảo

### Yêu cầu trường & kinh nghiệm thi
- [Review thực tế tiểu học Nguyễn Siêu](https://haysiri.com/reviews/review-thuc-te-luyen-thi-va-hoc-tai-truong-nguyen-sieu)
- [Mô hình lớp 1 & năng lực ngoại ngữ Nguyễn Siêu 2025-2026](https://nsps.edu.vn/vi/kham-pha-mo-hinh-lop-1-nam-hoc-2025-2026-va-nang-luc-ngoai-ngu-truong-tieu-hoc-nguyen-sieu)
- [Đề thi vào lớp 1 Đoàn Thị Điểm](https://situ.edu.vn/bo-de-thi-vao-lop-1-truong-tieu-hoc-doan-thi-diem-full-mon/)
- [Đề thi vào lớp 1 Đoàn Thị Điểm - Tiền Phong](https://tienphong.vn/de-thi-vao-lop-1-truong-doan-thi-diem-kho-the-nao-post622363.tpo)

### Lộ trình & phương pháp học toán tư duy
- [Toán tư duy cho trẻ chuẩn bị vào lớp 1 - LogicLab](https://logiclab.edu.vn/toan-tu-duy-cho-tre-chuan-bi-vao-lop-1/)
- [9 dạng bài tập toán tư duy mầm non - BMYC](https://bmyc.vn/toan-tu-duy-mam-non/)
- [Toán tư duy cho trẻ mầm non - Sylvan Learning](https://sylvanlearning.edu.vn/toan-tu-duy-cho-tre-mam-non/)
- [99+ bài tập toán tư duy 4-6 tuổi - Clevai](https://clevai.edu.vn/hieu-con-yeu/toan-tu-duy-cho-be-4-tuoi/)

### Phương pháp sư phạm
- [Phương pháp Montessori cho trẻ mầm non - Monkey](https://monkey.edu.vn/ba-me-can-biet/giao-duc/giao-duc-som/phuong-phap-montessori-cho-tre-mam-non)
- [Dạy toán theo phương pháp Montessori - Kinderlove](https://kinderlove.vn/blogs/phuong-phap-montessori/day-toan-theo-phuong-phap-montessori-hay)

### App tham khảo
- [Alostar - học tiếng Anh tích hợp trẻ mầm non](https://alostar.com.vn/)
- [5 app học toán tư duy tốt nhất cho trẻ mầm non](https://houston123.edu.vn/ung-dung-hoc-toan-tu-duy-cho-tre-em-mam-non/)

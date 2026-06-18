---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI Gia Sư Cá Nhân Hóa (Socratic Math Tutor)

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** Hệ thống AI Gia sư cá nhân hóa hỗ trợ học sinh học tập qua phương pháp Socratic.
- **Lát cắt tôi chọn để phân tích hôm nay là:** Giúp học sinh lớp 5 tự giải quyết các bài tập toán phân số khó tại nhà vào buổi tối khi gặp bế tắc.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là thời điểm học sinh dễ gặp bế tắc nhất trong ngày vì không có giáo viên bên cạnh. Lúc này, bố mẹ thường bận rộn hoặc thiếu kỹ năng sư phạm, dẫn đến việc học sinh dễ nản lòng và từ bỏ tự tư duy để chuyển sang sao chép lời giải đối phó trên mạng.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Học sinh bị hổng kiến thức toán nền tảng (như phân số) do lười suy nghĩ, sợ sai và có thói quen copy-paste lời giải có sẵn trên mạng để đối phó với bài tập về nhà mà không hiểu bản chất.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Học sinh tiểu học (lớp 5) đang trong giai đoạn chuyển đổi tư duy số học phức tạp và chuẩn bị lên cấp hai.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Lên mạng tra cứu đáp án trực tiếp (VietJack, Loigiaihay), hỏi bố mẹ (nhưng bố mẹ thường bận hoặc cho luôn đáp số thay vì giảng), hoặc bỏ trống không làm.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Học sinh lớp 5 đang học các chủ đề Toán phức tạp (phân số, số thập phân) và gặp khó khăn với bài tập tự học.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Lúc tự làm bài tập về nhà vào buổi tối tại nhà, không có giáo viên đồng hành và không có trợ giúp sư phạm chất lượng.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Chép lời giải từ các trang web giải bài tập trực tuyến, nhờ bố mẹ làm hộ hoặc chịu phạt trước lớp vào ngày hôm sau.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Sự phát triển của các công nghệ AI Agent (LangGraph, LLM Function Calling) cho phép tạo ra các chatbot có khả năng đối thoại Socratic kiên nhẫn, cá nhân hóa theo trình độ học sinh, điều mà các công cụ tìm kiếm tĩnh hay sách giải không bao giờ làm được.

### Tóm tắt market context trong 3-4 dòng

> Học sinh lớp 5 thường gặp bế tắc khi tự làm bài tập toán phân số khó tại nhà vào buổi tối. Việc thiếu hụt sự trợ giúp sư phạm kịp thời khiến các em dễ nản lòng và hình thành thói quen đối phó bằng cách sao chép lời giải trực tiếp trên mạng, gây ra lỗ hổng kiến thức nghiêm trọng khi chuyển cấp.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Học sinh lớp 5 đang tự học môn Toán tại nhà.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Học sinh là người trực tiếp làm bài tập về nhà, trực tiếp trải qua cảm giác bế tắc khi gặp bài khó, và trực tiếp tương tác với công cụ trò chuyện để tìm kiếm sự hỗ trợ nhằm hoàn thành bài tập của mình.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Giải quyết các bài tập toán phân số khó tại nhà để nộp cho giáo viên.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: Không có (tuy nhiên từ "để nộp cho giáo viên" mang tính đối phó hơn là bản chất công việc tự học).

### Bản chốt

**Core JTBD cuối cùng:**  
> Vượt qua bế tắc khi giải các bài tập toán phân số khó tại nhà để tự mình hoàn thành bài tập và hiểu bản chất kiến thức.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi con gặp một bài toán cộng hai phân số khác mẫu số phức tạp lúc 9 giờ tối và bị tắc ở bước quy đồng | Con muốn nhận được một gợi ý nhỏ hoặc một câu hỏi gợi mở để tự tìm ra mẫu số chung | Con tự mình giải quyết được phép tính mà không cần phải đi chép lời giải của người khác. | Học sinh cần một sự gợi ý đúng hướng ngay tại thời điểm bế tắc để tiếp tục tự suy nghĩ. |
| JS2 | Khi con tự tính ra kết quả phép chia số thập phân nhưng không chắc chắn phép tính của mình đúng hay sai | Con muốn có một công cụ kiểm tra và chỉ ra chính xác bước tính toán con bị nhầm lẫn | Con tự sửa lại bài làm của mình cho đúng trước khi nộp vở cho cô giáo vào sáng mai. | Học sinh cần xác nhận nhanh lỗi sai cụ thể (lỗi tính toán hay lỗi công thức) để sửa kịp thời. |
| JS3 | Khi con cảm thấy quá nản lòng và mệt mỏi sau 15 phút loay hoay mãi không giải được bài toán hình học | Con muốn nhận được một lời động viên và một câu hỏi thử thách nhỏ dễ hơn liên hệ với đời thực | Con lấy lại sự tự tin và tiếp tục kiên trì học tập thay vì bỏ cuộc và đóng sách lại đi chơi. | Yếu tố tâm lý và nhu cầu chia nhỏ độ khó của bài học để duy trì sự kiên trì của học sinh. |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Trang web giải bài tập (VietJack, Loigiaihay) | Tìm kiếm lời giải đầy đủ để sao chép vào vở bài tập. | Rất nhanh, miễn phí, luôn có sẵn đáp án cuối cùng cho mọi bài tập SGK. | Học sinh chỉ copy-paste đối phó, không hiểu cách làm, dễ bị hổng kiến thức nghiêm trọng và bị giáo viên phạt khi kiểm tra trực tiếp. | Cực kỳ thấp (chỉ cần Google search là ra ngay). |
| Bố mẹ kèm cặp | Nhờ giảng bài và kiểm tra đáp số bài làm. | Có sự tương tác thực tế, tạo cảm giác yên tâm và áp lực học tập cần thiết. | Bố mẹ thường bận việc, dễ nổi nóng khi con không hiểu, thiếu kỹ năng sư phạm (thường giải hộ luôn hoặc quát mắng làm trẻ sợ). | Trung bình (phụ thuộc vào thời gian rảnh và sự kiên nhẫn của bố mẹ). |
| Đi học thêm / Gia sư truyền thống | Được dạy lại lý thuyết và hướng dẫn giải bài tập trực tiếp. | Giáo viên có chuyên môn, giải thích cặn kẽ các dạng bài. | Chi phí rất cao, thời gian học cố định, không thể hỗ trợ tức thời vào lúc đêm muộn khi học sinh đang làm bài tại nhà. | Cao (đòi hỏi chi phí hàng tháng và thời gian đưa đón học tập). |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Sao chép lời giải trên mạng để đối phó nhanh với bài tập về nhà, hoặc chịu chấp nhận hổng kiến thức toán và ỷ lại vào bố mẹ.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Hiểu yêu cầu đề bài toán (biết đề cho gì và hỏi gì). | Đọc đề bài trong SGK, gạch chân các con số chính. | Đề bài toán đố lớp 5 lắt léo, dùng ngôn từ ẩn dụ làm học sinh không hiểu phải thực hiện phép tính gì. | Med |
| Locate | Tìm kiếm công thức và lý thuyết liên quan để áp dụng. | Lật lại các trang lý thuyết cũ trong sách giáo khoa, vở ghi. | Kiến thức phân bố rải rác, học sinh không biết bài toán thực tế này tương ứng với công thức nào trong sách. | High |
| Prepare | Chuẩn bị công cụ và không gian nháp. | Vở nháp, bút, thước kẻ, máy tính bỏ túi. | Không có friction đáng kể. | Low |
| Confirm | Xác nhận hướng đi đúng trước khi đặt bút tính toán chính thức. | Tự nhẩm hướng đi trong đầu hoặc hỏi bố mẹ để xin xác nhận xem hướng giải này đúng chưa. | Cảm giác mơ hồ, sợ tính sai mất công nên không dám đặt bút làm, dễ từ bỏ để đi chép đáp án. | High |
| Execute | Thực hiện tính toán các phép tính phân số/số thập phân. | Tính nhẩm hoặc đặt phép tính chia/nhân chéo ra giấy nháp. | Phép tính phân số/số thập phân nhiều bước nhỏ, học sinh rất dễ tính toán nhầm lẫn giữa chừng. | Med |
| Monitor | Giám sát tiến độ và kiểm tra xem kết quả nháp có đúng không. | Nhìn lại kết quả cuối cùng, tự nhẩm lại hoặc so sánh với bài của bạn bè qua Zalo. | Không có đáp số chuẩn để đối chiếu trực tiếp, hoặc nếu kết quả sai cũng không biết mình bị sai ở dòng nào. | High |
| Modify | Sửa đổi phép tính và cách giải khi phát hiện kết quả sai hoặc bị tắc. | Tẩy xóa viết lại từ đầu hoặc vò nát giấy nháp khi làm sai nhiều lần. | Cực kỳ nản lòng vì phải tính lại từ đầu mà không biết lỗi sai cụ thể ở đâu, dễ phát sinh cảm xúc tiêu cực. | High |
| Conclude | Hoàn thành bài toán và trình bày lời giải chính thức vào vở. | Viết lời giải nộp bài bằng bút mực. | Trình bày lời giải toán đố phải viết câu thuyết minh dài dòng, học sinh tiểu học ngại viết chữ. | Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** `Locate` (Tìm kiếm và liên kết đúng kiến thức lý thuyết SGK vào bài tập thực tế trước mắt).  
**Bước đau nhất #2:** `Modify` (Nhận diện lỗi sai và điều chỉnh phép toán khi bị bế tắc mà không bị nản chí).

**Vì sao đây là nơi đáng chú ý nhất:**  
> Tại bước `Locate`, học sinh bị tắc vì không biết áp dụng công thức nào, dẫn đến không thể bắt đầu làm bài. Tại bước `Modify`, học sinh bị nản lòng vì làm sai mà không biết sai ở đâu. Đây là 2 thời điểm nhạy cảm nhất kích hoạt hành vi từ bỏ học tập để đi chép lời giải.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| `Locate` (Tìm kiến thức) | AI sử dụng RAG truy xuất chính xác đoạn lý thuyết tương ứng của bài học từ SGK, kết hợp phương pháp Socratic để đưa ra câu hỏi gợi ý nhỏ (ví dụ: gợi nhớ khái niệm quy đồng) thay vì cung cấp lời giải. | AI có khả năng đọc hiểu ngữ cảnh bài toán của học sinh và liên kết tức thì với cơ sở dữ liệu tri thức của SGK chuẩn, sau đó biến đổi ngôn ngữ sư phạm mềm mỏng. | AI có thể viết quá dài dòng hoặc đưa ra thuật ngữ quá học thuật làm học sinh khó hiểu. |
| `Modify` (Sửa lỗi sai) | AI chạy ngầm bộ tính toán logic (Internal Calculator) kiểm tra chéo phép tính của học sinh, phát hiện chính xác lỗi (cộng tử với tử, mẫu với mẫu, nhầm số thập phân) để chỉ ra lỗi sai tư duy và hướng dẫn học sinh sửa lại. | AI kết hợp logic lập trình (deterministic calculator) giúp loại bỏ hiện tượng ảo giác tính toán của LLM, đảm bảo chẩn đoán lỗi sai toán học chính xác 100%. | Học sinh cố tình bẻ lái prompt (jailbreak) để ép AI đưa ra đáp số cuối cùng cho mình chép. |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Sử dụng AI Agent (LangGraph) để điều phối cuộc đối thoại Socratic, kết hợp công nghệ RAG lấy dữ liệu SGK chuẩn và bộ tính toán Python Calculator chạy ngầm để phát hiện và định hướng sửa lỗi sai cho học sinh ngay khi các em bị bế tắc.

**Vì sao không phải ở bước khác:**  
> Các bước khác như `Prepare` (Chuẩn bị dụng cụ) hay `Conclude` (Trình bày viết vở) là các thao tác vật lý hoặc ghi chép thuần túy, không cần đến khả năng nhận thức ngôn ngữ và suy luận sư phạm của AI.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
tiền đề họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **học sinh lớp 5 tự học Toán** giải quyết bế tắc ở bước **tìm kiến thức liên quan (Locate)** và **sửa đổi phép tính sai (Modify)**, bằng cách cung cấp một **AI Gia sư Socratic tương tác thời gian thực tích hợp RAG SGK và bộ tính toán nội bộ để chỉ ra lỗi sai mà không lộ đáp án**, thì học sinh sẽ chuyển từ việc **sao chép lời giải trên mạng hoặc ỷ lại vào bố mẹ** sang **học tập chủ động trên ứng dụng**, vì các em có thể **tự mình chinh phục bài toán khó, thực sự hiểu bài và có cảm giác thành tựu**.

### Tín hiệu sớm nếu hypothesis này đúng

1. Tỷ lệ học sinh bỏ ngang phiên học (drop-off rate) khi gặp các bài toán phân số nâng cao giảm dưới 15% sau tuần đầu tiên sử dụng.
2. Số lượt hội thoại trung bình giữa học sinh và AI (turns per session) tăng lên từ 4 đến 8 lượt, thể hiện học sinh chịu khó tương tác làm bài thay vì hỏi đáp số một lần rồi thoát.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| **A1:** Học sinh thực sự muốn tự hiểu bài toán thay vì chỉ muốn hoàn thành nhanh bài tập để đi chơi. | Nếu học sinh hoàn toàn lười biếng, các em sẽ ghét AI Socratic vì "hỏi nhiều mà không cho chép đáp án" và quay lại dùng các trang web giải bài. | Khảo sát hành vi học sinh lớp 5 cho thấy các em có cảm giác tự hào lớn khi tự mình giải được bài khó trước lớp. | Thử nghiệm thực tế (A/B testing) giữa nhóm dùng AI Socratic gợi mở và nhóm dùng AI cho đáp án luôn, đo lường tỷ lệ giữ chân (retention rate). |
| **A2:** AI Socratic không gây ức chế hoặc làm học sinh bực bội khi liên tục hỏi ngược. | Nếu giọng điệu AI quá cứng nhắc hoặc hỏi quá khó, học sinh sẽ cảm thấy bị thách đố và nản lòng hơn. | Các Persona AI (Anh trai hài hước, Chị gái nhẹ nhàng) giúp làm giảm căng thẳng tâm lý học sinh khi trò chuyện. | Thực hiện user testing trực tiếp với 10-15 học sinh, quan sát biểu cảm khuôn mặt và ghi âm lại suy nghĩ của các em khi chat với AI. |
| **A3:** Công nghệ RAG và Calculator đảm bảo AI không bao giờ bị ảo giác đưa ra gợi ý sai kiến thức. | Học sinh tiểu học rất tin tưởng giáo viên. Một gợi ý sai của AI sẽ làm các em hoang mang và phụ huynh mất lòng tin ngay lập tức. | Bộ tính toán Python Calculator nội bộ đã chạy pass 100% các test case tính toán phân số/số thập phân lớp 5 phức tạp. | Chạy bộ test tự động (evaluation suite) với 500 bài toán lớp 5 khác nhau để đo lường tỷ lệ gợi ý sai lệch của AI. |
| **A4:** Phụ huynh tin tưởng và sẵn sàng trả tiền để con tự học cùng AI thay vì thuê gia sư truyền thống. | Phụ huynh là người trả tiền. Nếu họ không thấy tiến trình học tập của con rõ ràng, họ sẽ ngừng gia hạn tài khoản. | Giao diện Dashboard dành riêng cho phụ huynh báo cáo chi tiết thời gian tự học và các lỗ hổng kiến thức toán của con. | Phỏng vấn sâu 20 phụ huynh có con học lớp 5 để đo lường mức độ sẵn sàng chi trả (Willingness to Pay) cho dashboard này. |
| **A5:** Giáo viên chấp nhận cho học sinh sử dụng AI này như một công cụ bồi dưỡng bài tập về nhà. | Nếu giáo viên cấm vì sợ học sinh lười học, ứng dụng sẽ khó tiếp cận học sinh diện rộng. | Tính năng Classroom cho phép giáo viên quản lý lớp học, phân phối bài và giám sát tiến độ thực tế của từng học sinh. | Chạy thử nghiệm thí điểm (Pilot run) tại 2 lớp học của trường tiểu học đối tác trong vòng 1 tháng. |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **Học sinh có đủ kiên nhẫn để tương tác Socratic (hỏi-đáp từng bước nhỏ) thay vì từ bỏ ứng dụng để quay lại sao chép lời giải nhanh trên các trang mạng.** (Nếu assumption này sai, mô hình Socratic của sản phẩm sẽ thất bại hoàn toàn vì không thể giữ chân người dùng).

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai:** Học sinh lớp 5 tự học Toán tại nhà vào buổi tối.
2. **Core JTBD của bạn là gì:** Vượt qua bế tắc khi giải bài toán phân số khó tại nhà để tự hoàn thành bài và hiểu bản chất.
3. **Step đau nhất đang nằm ở đâu:** Locate (Tìm lý thuyết SGK áp dụng vào bài) và Modify (Sửa lỗi sai khi bế tắc phép tính).
4. **AI leverage point + assumption rủi ro nhất là gì:** Dùng AI Agent Socratic + RAG + Calculator chỉ lỗi sai toán học. Assumption rủi ro nhất là học sinh thiếu kiên nhẫn và từ bỏ app để đi chép giải cho nhanh.

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. "Câu JTBD này có đang lỡ nhét solution vào không?"
2. "Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"
3. "Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"
4. "Assumption nào nếu sai thì cả hypothesis sẽ sập?"

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| "Trẻ em lớp 5 rất ham chơi, nếu AI hỏi quá 3 lượt mà không ra kết quả, các em sẽ tắt app ngay để lên VietJack chép bài." | Assumption A1 và A2 (Sự kiên nhẫn của học sinh). | Sửa: AI cần có cơ chế thưởng điểm (Gamification), Streak và Badge tức thời sau mỗi bước tương tác đúng để duy trì động lực, đồng thời giới hạn số lượt hỏi Socratic tối đa 4 lượt trước khi đưa ra gợi ý siêu chi tiết. |
| "Phụ huynh mới là người trả tiền và giám sát, cần phân tích rõ vai trò của phụ huynh trong quyết định thuê sản phẩm." | Job Executor vs Buyer. | Giữ nguyên Job Executor là Học sinh vì học sinh trực tiếp làm bài, nhưng bổ sung tính năng Phụ huynh vào hypothesis như một tác nhân thúc đẩy (influencer/buyer). |
| "Làm thế nào để giáo viên tin tưởng AI không dạy sai phương pháp sư phạm của trường?" | Assumption A5 (Sự đồng thuận của giáo viên). | Sửa: AI RAG cần bám sát đúng bộ sách giáo khoa (Kết nối tri thức, Chân trời sáng tạo...) mà lớp học của học sinh đang sử dụng trên trường. |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [x] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Tôi giữ nguyên Job Executor và Core JTBD vì chúng phản ánh đúng bản chất trải nghiệm học tập của học sinh. Tôi sửa Product Hypothesis để bổ sung thêm cơ chế kích thích động lực (Gamification) và sự cá nhân hóa theo SGK của trường học, nhằm giải quyết triệt để rủi ro học sinh thiếu kiên nhẫn từ bỏ app.

### Version cuối cùng tôi nộp

**Job executor:**  
> Học sinh lớp 5 đang tự học môn Toán tại nhà vào buổi tối.

**Core JTBD:**  
> Vượt qua bế tắc khi giải các bài tập toán phân số khó tại nhà để tự mình hoàn thành bài tập và hiểu bản chất kiến thức.

**2 bước đau nhất trong workflow:**  
> 1. `Locate` (Tìm kiếm và liên kết đúng lý thuyết SGK vào bài tập thực tế trước mắt).  
> 2. `Modify` (Nhận diện lỗi sai và điều chỉnh phép toán khi bị bế tắc).

**AI leverage point chính:**  
> Sử dụng AI Agent (LangGraph) điều phối cuộc đối thoại Socratic sư phạm, tích hợp RAG SGK truy xuất chính xác lý thuyết và bộ tính toán Python Calculator chạy ngầm để chẩn đoán lỗi sai toán học của học sinh.

**Product hypothesis:**  
> Nếu chúng ta giúp **học sinh lớp 5 tự học Toán** giải quyết bế tắc ở bước **tìm kiến thức liên quan (Locate)** và **sửa đổi phép tính sai (Modify)** bằng cách cung cấp một **AI Gia sư Socratic tương tác thời gian thực tích hợp RAG SGK của trường học và bộ tính toán nội bộ để chỉ ra lỗi sai**, kết hợp **hệ thống điểm thưởng gamification tức thời**, thì học sinh sẽ chuyển từ việc **sao chép lời giải trên mạng** sang **tự học trên ứng dụng**, vì các em có thể **tự mình chinh phục bài toán khó một cách vui vẻ, thực sự hiểu bài và có cảm giác thành tựu**.

**Assumption cần validate đầu tiên:**  
> Học sinh có đủ sự kiên nhẫn và động lực để tương tác Socratic (hỏi-đáp từng bước nhỏ cùng AI) thay vì từ bỏ ứng dụng để quay lại sao chép lời giải nhanh trên các trang web giải bài tập có sẵn.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.

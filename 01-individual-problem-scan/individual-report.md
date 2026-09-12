# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Hà Anh Tuấn
- Mã học viên: 2A202602376
- Vai trò / bối cảnh : Sinh viên năm 3
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
• Làm dự án
• Kiểm tra email
• Viết daily standup
• Review báo cáo/assignment trước khi nộp
 

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Lặp lại|Check email |Bản thân |5'/ngày |
| 2 |Lặp lại|Theo dõi nhiều deadline cùng lúc|Bản thân|10'/ngày|
| 3 |Lặp lại|Viết daily standup |Bản thân |15'/ngày |
| 4 |AI có thể tốt hơn|Tìm tài liệu cho dự án|Cả nhóm|30-60'/lần, 2-3 lần/tuần|
| 5 |Tốn thời gian|Tìm lỗi trong báo cáo|Bản thân|30'/lần|
| 6 |Tốn thời gian|Không có tracking tool nên khi leader hỏi tiến độ, phải hỏi từng team member|Bản thân|20-30'/lần, 1-2 lần/tuần|
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi là sinh viên năm 3 đang làm dự án. Công việc hằng tuần gồm: Kiểm tra email, Viết daily standup report, Tìm tài liệu. Hãy gợi ý thêm problem theo 4 lăng kính. Đừng đưa ý tưởng quá rộng.
- Ý dùng được: 4 (Tìm tài liệu), 6 (Không có tracking tool, phải hỏi từng member)
- Ý bỏ vì không phải pain thật: Các ý khác của AI quá rộng (kiểu "xây trợ lý AI toàn năng") hoặc không có workflow cụ thể

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tìm tài liệu cho dự án | Workflow rõ, tốn 30-60'/lần (2-3 lần/tuần = 2-3 giờ/tuần), AI có thể hỗ trợ tìm kiếm/gợi ý; cả nhóm gặp vấn đề | Tiêu chí "tìm được đúng tài liệu" định nghĩa thế nào, có độ đo nào không |
| 2 | Tìm lỗi trong báo cáo | Pain cụ thể (30'/lần), metric rõ ràng, AI có thể giúp phát hiện lỗi | Loại lỗi nào? Chi tiết báo cáo là gì? |
| 3 | Viết daily standup | Lặp lại hằng ngày, cùng format, AI có thể draft; dễ validate nhanh | Format standup có chuẩn không, mục tiêu standup là gì |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tìm tài liệu cho dự án]

```text
Problem 1 câu:
Khi cần tài liệu cho dự án, tôi mất 30-60 phút mỗi lần tìm kiếm trong nhiều kho tài liệu khác nhau (wiki, Google Drive, Slack, email), dễ bỏ sót hoặc lấy sai phiên bản.

Actor:
Sinh viên/thành viên dự án (bản thân hoặc cả nhóm) cần tìm tài liệu, spec, hướng dẫn để thực hiện công việc.

Thời điểm / bối cảnh:
Khi bắt đầu task mới, cần hiểu requirement hoặc tìm reference document. Xảy ra nhiều lần/tuần.

Current workflow 3-7 bước:
1. Nhớ tài liệu ở đâu (hoặc Google/Slack search)
2. Mở multiple kho (wiki, Drive, Slack history, email)
3. Tìm keyword trong từng kho
4. Mở và đọc nhiều kết quả để lọc đúng file
5. Kiểm tra phiên bản (cũ hay mới?)
6. Copy/link tài liệu vào task
7. Nếu không tìm được, hỏi người khác

Bottleneck:
Bước 2-4: tìm kiếm phân tán trên nhiều platform (wiki, Drive, Slack, email). Không có chỗ tìm tập trung. Dẫn đến mất 30-60 phút/lần.

Impact:
Tôi mất 30-60 phút/lần, xảy ra ~2-3 lần/tuần → khoảng 2-3 giờ/tuần. Cả nhóm cùng vấn đề. Dễ miss deadline vì lấy tài liệu chậm.

Success metric:
Giảm thời gian tìm từ 30-60 phút xuống dưới 5 phút; tìm được tài liệu đúng (version đúng, spec đúng) lần đầu ≥80% trường hợp.

Non-AI alternative:
Tập trung tài liệu vào 1 Drive/wiki, có checklist tiêu chuẩn naming. Nhưng vẫn cần con người tìm, và sẽ mất thời gian reorganize.

AI hypothesis:
AI tìm kiếm qua nhiều kho + gợi ý ranking file theo relevance. Hoặc AI tóm tắt file để biết nhanh có phải file cần không.

Quick gut:
Workflow
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 30-60 phút

[1 Nhớ/tìm kho: 5']
→ [2 Mở multiple kho: 5']
→ [3 Tìm keyword (Slack, Drive, email): 15-30']  <-- bottleneck
→ [4 Kiểm tra phiên bản: 10']
→ [5 Copy/link vào task: 5']

FUTURE STATE — 5 phút

[1 User gõ query về tài liệu cần: 1']
→ [2 AI search + rank kết quả từ Wiki/Drive/Slack: 2']  <-- AI boundary
→ [3 User review top 3 kết quả + click: 2']  <-- human boundary

Fallback: AI không tìm được hoặc tìm sai → user manual search hoặc hỏi người khác.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Tìm lỗi trong báo cáo

```text
Problem 1 câu:
Khi review báo cáo của mình (assignment, lab report, weekly update), mất khoảng 30 phút/lần để đọc từ đầu đến cuối, tìm typo, sai số, logic không nhất quán.

Actor:
Bản thân (sinh viên/PM) cần review báo cáo trước khi nộp hoặc gửi cho người khác.

Thời điểm / bối cảnh:
Trước khi submit báo cáo hoặc gửi cho leader review. Tầu suất: ~1-2 báo cáo/tuần.

Current workflow 3-7 bước:
1. Viết draft báo cáo (Docs, Markdown, PDF)
2. Self-read toàn bộ từ đầu đến cuối
3. Tìm typo/spell check
4. Kiểm tra số liệu (công thức tính, tổng đúng không)
5. Kiểm tra consistency (tên, format)
6. Kiểm tra logic (kết luận có match data không)
7. Nộp

Bottleneck:
Bước 2-6: phải đọc toàn bộ doc, tìm lỗi thủ công. Dễ miss lỗi vì mắt mỏi hoặc logic phức tạp. Mất ~30 phút/báo cáo.

Impact:
Mất 30 phút × 1-2 báo cáo/tuần = ~30-60 phút/tuần. Nhưng lỗi miss ra có thể dẫn đến mất điểm hoặc phải sửa lại ngoài giờ.

Success metric:
Giảm thời gian review từ 30 phút xuống dưới 10 phút; phát hiện được ≥80% lỗi (typo, số, logic) mà human review sẽ tìm.

Non-AI alternative:
Dùng tool spell check built-in (Google Docs, Grammarly). Nhưng chưa giải quyết lỗi logic, consistency, số liệu.

AI hypothesis:
AI scan báo cáo, flagging typo, số liệu bất thường (so công thức), logic không match. Cấp 1: spell/grammar; Cấp 2: số liệu; Cấp 3: logic.

Quick gut:
Workflow
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30 phút

[1 Viết draft: không tính]
→ [2 Self-read toàn bộ: 10']
→ [3 Tìm typo: 5']
→ [4 Kiểm tra số liệu: 10']  <-- bottleneck
→ [5 Kiểm tra logic: 5']
→ [6 Nộp: <1']

FUTURE STATE — 10 phút

[1 Upload/paste báo cáo vào AI checker: 1']
→ [2 AI scan (typo, số liệu, logic): 2']  <-- AI boundary
→ [3 User review suggestions + fix: 7']  <-- human boundary
→ [4 Nộp: <1']

Fallback: AI report sai hoặc suggest không cần thiết → user skip.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Viết daily standup

```text
Problem 1 câu:
Mỗi sáng viết standup (done/doing/blocker) theo cùng format, mất khoảng 15 phút. Lặp lại hằng ngày nên dễ thấy là công việc có thể AI hỗ trợ.

Actor:
Bản thân (sinh viên/thành viên dự án) viết standup update.

Thời điểm / bối cảnh:
Hằng ngày sáng (9 AM hoặc trước standup meeting), trên Slack hoặc Notion. Workflow: nhớ lại hôm qua làm gì, hôm nay sẽ làm gì, có blocker gì.

Current workflow 3-7 bước:
1. Mở Slack/Notion standup template
2. Nhớ lại hôm qua làm (done)
3. Plan hôm nay (doing)
4. Nghĩ blocker
5. Viết lại thành câu đầy đủ
6. Format theo template
7. Post

Bottleneck:
Bước 2-5: phải nhớ, tổng hợp, và viết thành prose. Format đôi khi lộn xộn. Mất ~15 phút/ngày.

Impact:
15 phút/ngày × 5 ngày/tuần = 75 phút/tuần. Cùng với check email + deadline pressure + daily standup, tổng công việc meta (non-delivery) khá lớn.

Success metric:
Giảm thời gian từ 15 phút xuống 3-5 phút; standup format luôn consistent và đủ thông tin.

Non-AI alternative:
Template + checklist. Nhưng vẫn cần viết lại thành câu.

AI hypothesis:
AI hỏi quick input (3-5 bullet point), tự draft standup text chuẩn format. User chỉnh sửa 1-2 chỗ rồi post.

Quick gut:
Workflow
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 15 phút

[1 Mở template: 1']
→ [2 Nhớ hôm qua + plan hôm nay: 7']
→ [3 Viết thành câu: 5']  <-- bottleneck
→ [4 Format: 1']
→ [5 Post: 1']

FUTURE STATE — 5 phút

[1 User quick input (3-5 bullet): 2']
→ [2 AI draft standup text: 1']  <-- AI boundary
→ [3 User review + edit: 1']  <-- human boundary
→ [4 Post: <1']

Fallback: AI draft quá formal hoặc sai → user bỏ draft và viết tay.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Tìm tài liệu cho dự án
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow rõ: cần gì → search nhiều kho → lấy đúng file → dùng. Có thể vẽ before/after workflow rất rõ. Impact đo được: giảm từ 30-60 phút xuống <5 phút. Vấn đề gặp cả nhóm (không chỉ bản thân), nên validation sẽ dễ.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm sao định nghĩa "tài liệu đúng"? Cách nào để AI biết file user cần là file nào (relevance ranking)?
2. Nếu tài liệu nằm trong file private/permission-restricted (VD: email, closed Slack channel), AI có access được không?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Scope của "tài liệu" quá rộng (spec? code? doc? video?). Chưa rõ các kho tài liệu có API public hay không. Baseline "tìm kiếm cũ" mơ hồ—giả định sử dụng Google search hay Slack search?
- Tôi sửa gì: Thu hẹp scope sang "tài liệu text" (spec, doc, guide) trong 3 kho chính (Wiki, Google Drive, Slack). Baseline: đếm số phút actual spend khi tìm kiếm trên 5 task mẫu.

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge

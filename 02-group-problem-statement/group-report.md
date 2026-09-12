# 02 — Group Problem Statement

> Bản draft nhóm dựa trên candidate do Trần Đình Duy đề xuất. Các thành viên, quote validation và quyết định đồng thuận chưa có trong workspace nên được đánh dấu rõ; cần nhóm xác nhận trước khi nộp chính thức.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò |
|---:|---|---|---|
| 1 | Trần Đình Duy | 2A202602631 | Đề xuất candidate, workflow và metric |
| 2 | Chưa cung cấp | Chưa cung cấp | Cần nhóm điền |
| 3 | Chưa cung cấp | Chưa cung cấp | Cần nhóm điền |
| 4 | Chưa cung cấp | Chưa cung cấp | Cần nhóm điền |

**Candidate problem nhóm đề xuất:** Sinh viên mất thời gian chuyển requirement rải rác trong README/worksheet/guide thành task có thể theo dõi và dễ bỏ sót điều kiện nộp; cần kiểm tra xem checklist/rule đã đủ hay AI chỉ nên hỗ trợ một bước draft.

## Phase 3 — Group Convergence

### 3.1. Candidate top 3

Bảng dưới là các candidate đã có từ bản scan cá nhân. Các dòng còn lại cần lấy từ pitch thật của thành viên nhóm, không tự điền thay.

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---:|---|---|---|---|---|
| 1 | Trần Đình Duy | Chuyển requirement assignment thành task/checklist | Sinh viên làm lab/project | Đọc chéo guide và kiểm tra thiếu sót trước nộp | Có actor/output rõ, có thể thử bằng checklist |
| 2 | Trần Đình Duy | Tìm và tổng hợp kiến thức AI từ nhiều nguồn | Sinh viên tự học AI | Lọc nguồn và nối thành kết luận | Cần kiểm source, scope có thể rộng |
| 3 | Trần Đình Duy | Debug lỗi code qua nhiều vòng thử | Sinh viên coding | Chẩn đoán nguyên nhân giữa code và environment | Có metric nhưng cần phân loại lỗi |
| 4-12 | Thành viên nhóm | Chưa có biên bản pitch | Chưa xác định | Chưa xác định | Cần bổ sung sau buổi pitch |

### 3.2. Cluster đề xuất

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Information-to-action | Requirement-to-task, checklist nộp bài, tìm lại guide | Biến thông tin rời rạc thành hành động có thể theo dõi | Candidate được đề xuất đào sâu |
| B — Information discovery | Tìm kiến thức AI, tìm command/note cũ, tìm conversation | Tìm và lọc thông tin giữa nhiều nguồn | Có thể cần search/retrieval, scope rộng |
| C — Coding support | Debug error, copy/paste hỏi AI, test hồi quy | Giảm vòng lặp chẩn đoán và sửa code | Cần log lỗi để đo |
| D — Collaboration | Hỏi lại task/status, giải thích lại cho thành viên | Giảm mất mát context trong nhóm | Cần dữ liệu chat/task thật |

### 3.3. Shortlist và score sơ bộ

Điểm dưới đây là **đánh giá sơ bộ của người đề xuất**, chưa phải điểm đồng thuận của cả nhóm.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A | Nhóm hiểu domain | Tổng sơ bộ |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Requirement-to-task | 5 | 5 | 2 | 4 | 5 | 5 | 4 | 30 |
| Tìm/tổng hợp kiến thức AI | 5 | 4 | 2 | 3 | 4 | 4 | 4 | 26 |
| Debug lỗi code | 5 | 5 | 3 | 4 | 5 | 4 | 5 | 31 |

**Candidate đề xuất chọn:** Requirement-to-task và checklist tiến độ.

**Vì sao:** Actor là sinh viên, input là bộ requirement có sẵn và output là task/checklist cụ thể. Workflow tuyến tính, dễ vẽ trước/sau và có phương án non-AI rõ. Rủi ro của AI có thể giới hạn bằng link nguồn, review bắt buộc và không tự đánh dấu hoàn thành. Candidate này cũng cho phép nhóm trả lời trung thực nếu kết luận cuối là Rule/checklist đủ, không cần AI.

**Vì sao chưa chọn các candidate khác:** Tìm kiến thức AI có pain nhưng chất lượng “đã hiểu đúng” khó đo và phụ thuộc nhiều nguồn. Debug code có giá trị nhưng cần log nhiều lỗi và tách nguyên nhân môi trường khỏi nguyên nhân logic; đó là scope phù hợp cho một lab khác.

**Disagreement:** Chưa có biên bản disagreement thật. Cách xử lý đề xuất: mỗi thành viên chấm độc lập 1-5, ghi lý do cho điểm 3 và 5, sau đó dùng baseline/evidence để chốt thay vì vote theo độ “ngầu” của solution.

## Phase 4 — Validation và research

### 4.1. Quick validation

Chưa có interview/survey thật trong workspace. Không dùng số giả hoặc quote giả để kết luận pain của cả nhóm.

| Nguồn | Số người / mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa thực hiện | Chưa có quote | Chưa biết | Phỏng vấn 2-3 sinh viên đã làm assignment gần đây; hỏi thời gian planning và requirement bỏ sót. |
| Survey / poll | Chưa thực hiện | Chưa có dữ liệu | Chưa biết | Nếu nhiều người chỉ cần checklist, hạ scope AI xuống Rule/process fix. |
| Log / ticket / review | Chưa có log nhóm | Bản scan cá nhân cho thấy workflow lặp lại | Chưa đủ đại diện | Ghi 3 assignment: thời gian planning, số task, số thiếu sót trước nộp. |

**Insight hiện tại:** Đây là giả thuyết từ trải nghiệm cá nhân, chưa phải kết luận của nhóm. Pain có khả năng nằm ở việc nối requirement với hành động và kiểm tra coverage, nhưng cần validation để biết AI có tạo giá trị vượt template hay không.

**Kế hoạch validation tối thiểu:** hỏi 3 sinh viên, lấy 3 assignment thật, ghi thời gian planning trước checklist; thử một template không AI; chỉ mở rộng sang AI nếu template vẫn còn bước ngôn ngữ/diễn giải gây tốn thời gian.

### 4.2. Research giải pháp đã có

Các link dưới là trang chính thức để nhóm đọc và kiểm tra lại trước khi nộp. Chúng chứng minh các pattern quản lý task đã tồn tại, không chứng minh rằng AI sẽ giúp tiết kiệm một con số cụ thể.

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| GitHub Projects | [About Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) | Theo dõi issue/task, trạng thái và view | Hợp với workflow coding và repo | Không tự hiểu toàn bộ requirement nếu input chưa cấu trúc | Dùng project board/checklist làm non-AI baseline |
| Notion project management | [Using Notion for project management](https://www.notion.so/help/guides/using-notion-for-project-management) | Tạo task, owner, status, deadline và tài liệu liên quan | Gom note và task trong một nơi | Vẫn cần người đọc requirement và nhập dữ liệu | Chuẩn hóa schema task trước khi thêm AI |
| Trello guide | [Guide to Trello](https://support.atlassian.com/trello/docs/getting-started-with-trello/) | Chia card/list theo trạng thái | Dễ dùng cho checklist và theo dõi tiến độ | Không giải quyết trích xuất requirement phức tạp | Có thể pilot bằng board thủ công trước |

**Research takeaway:** Không nên xây Agent quản lý toàn bộ việc học ngay. Nhóm nên thử checklist/board trước; nếu bước đọc và chuyển requirement vẫn tốn công, dùng Workflow có AI draft task kèm link nguồn, sau đó sinh viên review. Không có AI nào được tự coi task là “đã hoàn thành” hoặc tự nộp bài.

## Phase 5 — Workflow và Problem Statement

### 5.1. Current workflow

```text
CURRENT STATE — baseline cần đo trên 3 assignment
[1 Đọc README/worksheet/guide: 20' - sinh viên]
 -> [2 Đánh dấu requirement/deadline: 10' - sinh viên]
 -> [3 Chia thành task trong note: 10' - sinh viên]
 -> [4 Làm và tự cập nhật: theo buổi học]
 -> [5 Đọc lại trước nộp: 5-20' - bottleneck]
 -> [6 Nộp và phát hiện thiếu nếu có]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Handoff / bottleneck |
|---:|---|---|---|---|---|
| 1 | Sinh viên | README, worksheet, guide | Nội dung cần hiểu | Khoảng 20', mỗi assignment | Từ tài liệu sang note |
| 2 | Sinh viên | Requirement và deadline | Danh sách điểm cần nhớ | Khoảng 10' | Dễ bỏ sót field |
| 3 | Sinh viên | Note rời rạc | Task cá nhân | Khoảng 10' | **Bottleneck: diễn giải thành task** |
| 4 | Sinh viên | Task và code | Trạng thái tạm | Trong suốt lab | Cập nhật thủ công |
| 5 | Sinh viên | Bài đã làm + guide | Checklist cuối | 5-20' | **Bottleneck: kiểm coverage** |
| 6 | Sinh viên/giảng viên | Bài nộp | Kết quả chấm | Sau deadline | Hậu quả nếu thiếu file/field |

**Bottleneck chính:** Bài toán không chỉ là tạo danh sách task; đó là giữ liên kết giữa task, requirement gốc và điều kiện nộp. Nếu không có link nguồn và bước review, AI có thể tạo task nghe hợp lý nhưng bỏ sót requirement quan trọng.

### 5.2. Future workflow

```text
FUTURE STATE — mục tiêu cần kiểm chứng, không phải kết quả đã đạt
[1 Nhập file guide: máy/parser 2']
 -> [2 Rule tách deadline/file/keyword: 3']
 -> [3 AI draft task + link đoạn nguồn: 3']
 -> [4 Sinh viên review và sửa: 15-20' - HUMAN BOUNDARY]
 -> [5 Checklist coverage + tự đánh dấu: 5']
 -> [6 Sinh viên tự nộp]

Fallback: parser/AI lỗi hoặc thiếu nguồn -> dùng checklist thủ công và đọc guide.
Cấm: tự đánh dấu hoàn thành, tự commit, tự submit hoặc tự quyết định requirement mơ hồ.
```

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian planning | Baseline cần đo trên 3 assignment | Giảm ít nhất 30% | Bấm giờ từ lúc mở guide đến checklist usable |
| Số bước | 6 bước | 5-6 bước | Đếm các handoff thực tế |
| Số bước thủ công | 6/6 | 2-3/5, vẫn có review | Ghi ai thực hiện từng bước |
| Requirement bị bỏ sót | Chưa biết | 0 trong 3 pilot | Đối chiếu checklist với guide sau nộp |
| Bottleneck | Diễn giải + kiểm coverage | Review task/nguồn | Ghi thời gian review và số task sửa |
| Risk mới | Bỏ sót do note rời rạc | AI trích sai hoặc bịa task | Audit link nguồn, rollback về checklist |

### 5.3. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên làm nhiều lab/assignment và phải tự theo dõi requirement, deadline, file nộp. |
| **Workflow** | Sinh viên đọc nhiều file, đánh dấu requirement, tự chia task, làm bài, cập nhật note và đọc lại trước khi nộp. |
| **Bottleneck** | Chuyển requirement rời rạc thành task có thể theo dõi và kiểm tra coverage trước deadline. |
| **Impact** | Có thể mất thêm thời gian đọc chéo, gián đoạn coding và bỏ sót file/field. Mức thời gian và tỷ lệ bỏ sót cần baseline thật. |
| **Success Metric** | Mục tiêu thử nghiệm: giảm 30% thời gian planning và không bỏ sót requirement trong 3 assignment; đo bằng timer và checklist đối chiếu. |
| **Boundary** | Công cụ chỉ draft task/checklist từ tài liệu được cung cấp; không tự đánh dấu hoàn thành, không tự nộp, không bịa requirement và không thay quyết định của sinh viên. |

**AI phản biện v0:** Metric cần baseline trước khi gọi là thành công; “task usable” cần định nghĩa bằng việc sinh viên chấp nhận hay sửa task; candidate cũng phải so với checklist không AI.

## Phase 6 — Rule / Workflow / Agent và quyết định

### 6.0. Ma trận phù hợp

- Độ mơ hồ: **Thấp đến trung bình**. Field như file nộp, deadline và keyword có thể kiểm bằng rule; diễn giải task có nhiều cách viết.
- Độ phức tạp: **Trung bình**. Có nhiều tài liệu và vài bước nối tiếp, nhưng đường đi chủ yếu tuyến tính, không cần tự lập kế hoạch động.

**Bài toán nằm ở ô:** Độ phức tạp trung bình, độ mơ hồ thấp/trung bình; Rule xử lý field cố định, Workflow có AI hỗ trợ phần draft ngôn ngữ.

### 6.1. So sánh Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Parser/checklist tách deadline, file, heading và keyword | Đủ nếu requirement có cấu trúc và nhóm chỉ cần coverage | Không hiểu câu mơ hồ hoặc dependency giữa task | Chọn làm baseline và safety check |
| **Workflow** | Parser/rule -> AI draft task có link -> sinh viên review -> checklist | Đủ khi có vài đoạn cần diễn giải nhưng đường đi cố định | Draft sai, thiếu requirement, phải audit nguồn | Chọn cho pilot nếu validation cho thấy checklist chưa đủ |
| **Agent** | Tự đọc nhiều nguồn, lập kế hoạch, gọi tool và tự cập nhật board | Chỉ hợp khi có nhiều nhánh và quyền thao tác rõ | Scope/permission quá rộng, tự đánh dấu sai hoặc submit | Không chọn |

1. **Rule có giải được 70-80% case không?** Chưa biết; cần đo trên 3 assignment. Dự kiến rule giải tốt field cố định, chưa chắc giải được task diễn giải.
2. **Các bước có đi thẳng không?** Có, phần lớn là đọc -> tách -> draft -> review -> checklist; không cần agent tự đổi kế hoạch.
3. **Có cần Agent tự lập kế hoạch và gọi tool không?** Chưa. Quyền tự sửa board hoặc submit làm tăng rủi ro mà chưa chứng minh giá trị.
4. **Nếu AI sai, ai sửa trong bao lâu?** Sinh viên review ngay trước khi đánh dấu task; thời gian sửa cần đo trong pilot.
5. **Có hạ từ Agent -> Workflow -> Rule không?** Có. Fallback là Workflow thủ công, thấp hơn nữa là checklist/board không AI.

**Mức chọn:** Rule + Workflow giới hạn, không dùng Agent.

**Vì sao chọn:** Rule đảm nhiệm phần có đáp án rõ; Workflow xử lý đoạn cần hiểu ngôn ngữ; sinh viên giữ quyền xác nhận. Cách này cho phép đo incremental value của AI thay vì giả định AI luôn cần thiết.

**Vì sao không chọn Agent:** Không cần tự lập kế hoạch động, dữ liệu đầu vào còn nhỏ và quyền tự thao tác có hậu quả trực tiếp đến việc nộp bài. Agent chỉ nên được xem xét sau khi có log cho thấy Workflow cố định không đủ.

### 6.2. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên làm assignment, chịu trách nhiệm hiểu requirement và nộp đúng file/field trước deadline. |
| **Workflow** | Đọc README/worksheet/guide -> tách requirement cố định bằng rule -> draft task có liên kết nguồn -> sinh viên review -> checklist coverage -> tự nộp. |
| **Bottleneck** | Diễn giải requirement rời rạc thành task và kiểm tra không bỏ sót trước nộp. |
| **Impact** | Giả thuyết cần kiểm chứng: planning chiếm thời gian đáng kể và thiếu requirement tạo rework. Không dùng con số này như evidence trước pilot. |
| **Success Metric** | Trên 3 assignment: giảm >=30% thời gian planning so với baseline cá nhân; 0 requirement bỏ sót; ghi tỷ lệ task AI draft bị sửa và số lỗi do draft. |
| **Boundary** | Làm: tách field, tạo draft task, giữ link nguồn. Không làm: tự đánh dấu hoàn thành, tự nộp, tự commit, bịa requirement, bỏ qua nội dung mơ hồ hoặc thay sinh viên quyết định. |
| **AI intervention point** | Sau bước parser/rule lấy requirement, trước bước sinh viên review và checklist coverage. |
| **Mức chọn** | Rule + Workflow giới hạn vì đường đi tuyến tính và con người cần kiểm soát đầu ra. |
| **Rủi ro & người kiểm tra** | Bỏ sót hoặc diễn giải sai; sinh viên đối chiếu từng task với nguồn, chạy pilot và rollback về checklist nếu audit không đạt. |

### 6.3. Final decision

| Câu hỏi | Trạng thái | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | Yes sơ bộ | Bối cảnh cá nhân rõ; cần nhóm xác nhận có cùng pain. |
| Baseline + metric đo được chưa? | Not Yet | Đã có cách đo, chưa có 3 assignment log. |
| Data/input đủ dùng chưa? | Not Yet | Có README/guide mẫu, cần chọn bộ pilot đại diện. |
| AI sai, hậu quả chấp nhận được không? | Yes có điều kiện | Không tự nộp và bắt buộc review; vẫn cần audit. |
| Có người review/owner không? | Yes | Sinh viên là owner và reviewer cuối. |
| Có cách non-AI đơn giản hơn không? | Yes | Checklist/template phải được thử trước. |

**Decision:** **Not Yet cho AI production; Go cho validation/pilot thủ công có kiểm soát.**

**Lý do:** Problem và workflow cá nhân đã rõ, nhưng bằng chứng nhóm, baseline và quote validation còn thiếu. Pilot nhỏ có rủi ro thấp vì output chỉ là draft và checklist. Nếu template không AI đã đạt mục tiêu, nhóm nên kết luận Rule/process fix đủ thay vì cố dùng AI.

**Pilot nhỏ nhất:** Chọn 3 assignment thật; lần 1 dùng quy trình hiện tại và bấm giờ; lần 2 dùng checklist/rule; chỉ sau đó thử AI draft task có link nguồn. Đo 3 số: thời gian planning, số requirement bỏ sót và tỷ lệ task draft bị sửa.

**Not Yet cần validate:** 2-3 interview hoặc 5-10 survey; 3 assignment log; kiểm tra nguồn; xác định “task usable” và tỷ lệ sửa chấp nhận được.

**Nếu No-Go:** Dùng template checklist + GitHub Projects/Trello/Notion, không dùng AI.

**Exit / rollback:** Dừng AI và quay về checklist nếu có task không có link nguồn, bỏ sót requirement trong pilot, sinh viên sửa phần lớn draft, hoặc output khiến thời gian tổng tăng.

## Self-check phần 02

- [x] Có convergence từ candidate cá nhân, cluster, shortlist và score sơ bộ.
- [ ] Có đủ 9-12 candidate và điểm đồng thuận thật của nhóm: cần bổ sung biên bản pitch.
- [ ] Có quote interview/survey thật: chưa thực hiện trong workspace.
- [x] Có research links chính thức và ghi rõ giới hạn claim.
- [x] Có workflow trước/sau, thời gian dự kiến, handoff, boundary và fallback.
- [x] Có PS v0 -> v1, metric trước/sau và cách đo.
- [x] Có so sánh Rule/Workflow/Agent và decision có điều kiện.

# 01 — Individual Problem Scan

> Bản cá nhân của Trần Đình Duy. Các số liệu chưa có log được ghi là baseline cần đo, không coi là evidence đã xác minh.

## Thông tin cá nhân

- Họ và tên: Trần Đình Duy
- Mã học viên: 2A202602631
- Vai trò / bối cảnh: Sinh viên năm cuối Đại học FPT Hà Nội
- Công việc hằng tuần: đi học, làm lab/project, tự học AI và tiếng Nhật, tìm tài liệu, debug code, quản lý nhiều deadline.

## Phase 1 — Scan 12 problems

| # | Lăng kính | Problem quan sát được | Actor | Workflow sơ bộ | Dấu hiệu thật / cách đo |
|---:|---|---|---|---|---|
| 1 | Lặp lại | Mỗi khi làm lab phải đọc lại guide nhiều lần để biết bước tiếp theo. | Bản thân | Nhận lab -> đọc guide -> code -> quay lại guide -> code. | Ghi số lần quay lại guide và tổng phút trong 5 lab. |
| 2 | Tốn thời gian | Khi code lỗi phải thử nhiều cách trước khi tìm đúng nguyên nhân. | Bản thân | Chạy -> đọc error -> search/AI -> sửa -> chạy lại. | Ghi thời gian debug, số vòng thử và số lần hỏi AI trên 5 lỗi. |
| 3 | Lặp lại | Phải copy error sang AI rồi copy câu trả lời về VS Code. | Bản thân | VS Code -> AI -> VS Code -> test. | Đếm vòng copy/paste trên 5 task coding. |
| 4 | Tốn thời gian | Tìm nhiều nguồn trước khi hiểu một khái niệm AI đủ để dùng. | Bản thân | Google -> video -> docs -> GitHub -> AI -> ghi chú. | Đo thời gian từ lúc tìm đến khi có ghi chú dùng được trên 5 chủ đề. |
| 5 | AI có thể tốt hơn | Tự lọc và tổng hợp thông tin quan trọng từ nhiều tutorial. | Bản thân | Đọc -> highlight -> ghi chú -> tổng hợp -> áp dụng. | Đo thời gian đọc/tổng hợp 3 tài liệu và số nguồn đã xem. |
| 6 | Lặp lại | Tìm lại command, setup hoặc cách sửa đã từng dùng ở project khác. | Bản thân | Nhớ mơ hồ -> tìm project cũ/GitHub/Google -> thử lại. | Ghi số lần tìm lại và số phút mỗi lần trong 1 tuần. |
| 7 | Tốn thời gian | Chuyển qua lại giữa VS Code, browser, GitHub, terminal, AI và docs. | Bản thân | Code -> browser -> AI -> GitHub -> terminal -> code. | Đếm số lần đổi tab trong 3 buổi học. |
| 8 | AI có thể tốt hơn | Sau buổi học phải tự tìm chủ đề chưa hiểu để học lại. | Bản thân | Học -> xem lại -> phát hiện gap -> tìm tài liệu -> học lại. | Ghi số topic và phút xử lý trong 5 buổi. |
| 9 | Pain từ người khác | Thành viên nhóm hỏi lại task, deadline hoặc người phụ trách. | Thành viên nhóm | Nhận task -> trao đổi -> làm -> hỏi status -> cập nhật. | Đếm câu hỏi lặp lại trong 1 tuần; chưa có log nhóm. |
| 10 | Lặp lại | Chuyển requirement assignment thành task và kiểm tra task đã xong. | Bản thân/nhóm | Đọc requirement -> chia task -> làm -> checklist -> nộp. | Đo phút planning và số requirement bỏ sót trên 3 assignment. |
| 11 | Tốn thời gian | Tìm lại file, note, link hoặc conversation AI cũ. | Bản thân | Nhớ vị trí -> tìm folder/chat/history -> mở -> tìm đoạn cần dùng. | Ghi số lần và phút mỗi lần trong 7 ngày. |
| 12 | Pain từ người khác | Một thành viên phải giải thích lại cùng một vấn đề nhiều lần. | Người biết / người hỏi | Hỏi -> giải thích -> làm -> mắc lại -> hỏi lại. | Ghi số lần giải thích lại trong 1 project. |

**AI dùng ở Phase 1:** Tôi tự scan trước, sau đó dùng AI để phản biện scope. AI gợi ý thêm các hướng search tài liệu và quản lý task; tôi bỏ các ý quá rộng không có actor hoặc workflow cụ thể.

## Phase 2 — Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Chuyển requirement thành task và theo dõi tiến độ | Actor, input/output và checklist rõ; có phương án non-AI; impact liên quan trực tiếp deadline. | Cần baseline trên 3 assignment. |
| 2 | Tìm và tổng hợp kiến thức AI từ nhiều nguồn | Xảy ra thường xuyên; có thể đo thời gian và kiểm nguồn. | Chưa biết AI tiết kiệm bao nhiêu mà không làm giảm chất lượng hiểu bài. |
| 3 | Debug lỗi code qua nhiều vòng thử | Có workflow cụ thể, metric thời gian debug và số vòng thử. | Cần phân biệt lỗi môi trường, dependency và lỗi logic. |

### Problem Card #1 — Requirement thành task

**Problem 1 câu:** Khi nhận assignment mới, sinh viên mất thời gian chuyển requirement dài thành task cụ thể và dễ bỏ sót deadline hoặc điều kiện nộp.

**Actor:** Sinh viên năm cuối làm nhiều lab/project song song.

**Bối cảnh:** Khi nhận README, worksheet, guide và test của assignment mới.

**Current workflow:** Đọc guide -> đánh dấu requirement -> tự chia task trong note -> làm và cập nhật thủ công -> đọc lại trước khi nộp.

**Bottleneck:** Đọc chéo nhiều tài liệu và kiểm tra thiếu sót trước khi nộp.

**Impact:** Làm gián đoạn coding và có thể thiếu file/tiêu chí dù code đã chạy. Chưa có baseline định lượng.

**Success metric:** Trên 3 assignment, giảm ít nhất 30% thời gian planning và có 0 requirement bị bỏ sót trong checklist cuối.

**Non-AI alternative:** Template checklist, calendar deadline và review checklist.

**AI hypothesis:** AI trích xuất requirement thành task kèm link nguồn; sinh viên kiểm tra và tự đánh dấu hoàn thành.

**Quick gut:** Rule + Workflow, chưa cần Agent.

```text
CURRENT STATE — ước tính cần đo trên 3 assignment
[Đọc guide: 20'] -> [Đánh dấu requirement: 10'] -> [Chia task: 10'] -> [Kiểm tra: 5-20']

FUTURE STATE — mục tiêu dưới 35 phút
[Template/rule tách field: 5'] -> [AI draft task + link nguồn: 3'] -> [Sinh viên review: 20'] -> [Checklist: 5']

Fallback: AI bỏ sót hoặc trích sai -> quay về guide và checklist thủ công.
Human boundary: sinh viên là người xác nhận requirement và quyết định nộp.
```

### Problem Card #2 — Tổng hợp kiến thức AI

**Problem 1 câu:** Khi chưa hiểu một khái niệm AI, sinh viên phải tìm nhiều nguồn rồi tự tổng hợp thành câu trả lời có thể áp dụng.

**Actor:** Sinh viên tự học AI và làm lab.

**Bối cảnh:** Khi gặp khái niệm mới hoặc lỗi cần hiểu nguyên lý.

**Current workflow:** Xác định câu hỏi -> tìm Google/video/docs/GitHub -> đọc và ghi chú -> hỏi AI -> tự kiểm bằng ví dụ.

**Bottleneck:** Lọc nguồn và nối thông tin thành kết luận có thể kiểm chứng.

**Impact:** Thời gian học kéo dài và có nguy cơ tin nhầm câu trả lời không có nguồn.

**Success metric:** Giảm 25% thời gian trên 5 chủ đề, mọi claim quan trọng có link hoặc nhãn “chưa xác minh”.

**Non-AI alternative:** Danh sách docs chính thức và template ghi chú nguồn.

**AI hypothesis:** AI gợi ý từ khóa, so sánh và đặt câu hỏi tự kiểm; không thay việc đọc nguồn gốc.

**Quick gut:** Workflow có AI hỗ trợ một bước.

```text
CURRENT STATE — cần đo trên 5 chủ đề
[Xác định câu hỏi: 5'] -> [Tìm nguồn: 20'] -> [Đọc/lọc: 25'] -> [Tổng hợp: 15']
FUTURE STATE — mục tiêu giảm 25%
[Tìm docs chính thức: 5'] -> [AI gợi ý cấu trúc: 5'] -> [Đọc/kiểm nguồn: 25']
Fallback: nguồn mâu thuẫn -> bỏ draft AI, quay về docs chính thức hoặc hỏi giảng viên.
```

### Problem Card #3 — Debug lỗi code

**Problem 1 câu:** Khi code lỗi, sinh viên lặp nhiều vòng đọc traceback, search, hỏi AI, sửa và chạy lại trước khi biết nguyên nhân thật.

**Actor:** Sinh viên làm lab Python/AI.

**Bối cảnh:** Khi chạy test, gọi SDK hoặc tích hợp nhiều file.

**Current workflow:** Chạy test -> đọc traceback -> search/AI -> sửa -> chạy lại -> ghi nguyên nhân sau khi pass.

**Bottleneck:** Chẩn đoán nguyên nhân khi lỗi liên quan môi trường, dependency hoặc nhiều file.

**Impact:** Gián đoạn học và có thể tạo lỗi hồi quy. Cần đo trên 5 lỗi, không suy diễn từ một lần.

**Success metric:** Giảm 25% thời gian debug trung vị, không giảm tỷ lệ test pass và không tăng lỗi hồi quy.

**Non-AI alternative:** Checklist debug, đọc traceback từ dưới lên, kiểm tra environment và test tái hiện tối thiểu.

**AI hypothesis:** AI giải thích traceback và nêu giả thuyết; sinh viên tự kiểm chứng, không chấp nhận patch mù.

**Quick gut:** Workflow có AI hỗ trợ.

```text
CURRENT STATE — cần đo trên 5 lỗi
[Chạy test: 2'] -> [Đọc traceback: 5'] -> [Search/AI: 10'] -> [Sửa/chạy lại: 20']
FUTURE STATE — mục tiêu giảm 25% thời gian trung vị
[Tạo repro: 5'] -> [AI nêu giả thuyết: 3'] -> [Sinh viên kiểm chứng: 15']
Fallback: không rõ nguyên nhân -> checklist debug và hỏi người hướng dẫn.
```

### Card muốn pitch nhất

Tôi pitch Card #1. Đây là workflow xuất hiện ở mọi assignment, có output cụ thể và có thể thử bằng checklist trước khi đầu tư AI. Câu hỏi challenge nhóm: baseline planning thực tế là bao nhiêu trên ít nhất 3 assignment, và template/rule đã giải đủ bao nhiêu phần trước khi cần AI?

**AI phản biện:** AI chỉ ra nguy cơ scope thành “trợ lý học tập toàn năng”. Tôi thu hẹp vào requirement-to-task, bắt buộc link nguồn, đo requirement bỏ sót và giữ sinh viên review.

## Self-check

- [x] Có 12 problems, dùng đủ 4 lăng kính.
- [x] Có top 3 cards với workflow, bottleneck, metric, non-AI alternative và fallback.
- [x] Có card pitch và câu hỏi challenge.
- [ ] Quote/interview thật: chưa thu thập, cần bổ sung trước khi claim pain của người khác.

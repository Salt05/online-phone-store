# Báo cáo Triển khai Lab 3 – Quản lý Dự án trên GitHub

Dự án: **Hệ thống bán điện thoại trực tuyến (`online-phone-store`)**
Repository: https://github.com/Salt05/online-phone-store

---

## 1. Thông tin Repository

| Thuộc tính | Giá trị thực tế |
| :--- | :--- |
| Repository | [`Salt05/online-phone-store`](https://github.com/Salt05/online-phone-store) |
| Trạng thái | Public |
| Nhánh mặc định | `main` |
| Quyền tài khoản thao tác | `Salt05` (Owner — Admin/Maintain/Push/Triage/Pull) |
| Collaborators hiện tại | `Salt05` (Phạm Minh Phát) |
| Lời mời đang chờ | 0 (chưa có GitHub username của Nguyễn Thành Công) |
| Tính năng Issues / Projects | Issues: `True` / Projects: `True` |
| Dữ liệu trước khi triển khai | Repository trống (0 branches, 0 commits, 0 milestones, 0 issues, 10 default labels) |

## 2. Danh sách Milestones

| # | Tiêu đề Milestone | Deadline (Kế hoạch) | Trạng thái | Open Issues | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| #1 | **Sprint 1 – Foundation** | `2026-10-29` | `open` | 9 | [Milestone #1](https://github.com/Salt05/online-phone-store/milestone/1) |
| #2 | **Sprint 2 – Shopping & Orders** | `2026-11-11` | `open` | 9 | [Milestone #2](https://github.com/Salt05/online-phone-store/milestone/2) |
| #3 | **Sprint 3 – Administration** | `2026-11-25` | `open` | 9 | [Milestone #3](https://github.com/Salt05/online-phone-store/milestone/3) |
| #4 | **Sprint 4 – Payment & Release R1** | `2026-12-09` | `open` | 7 | [Milestone #4](https://github.com/Salt05/online-phone-store/milestone/4) |

> Lưu ý: Deadline của Sprint 1 (`2026-10-29`) và Sprint 2 (`2026-11-11`) được giữ nguyên đúng theo bảng kế hoạch gốc.

## 3. Danh sách Labels

Tổng số Labels hiện có trên repository: **28** (gồm **18** labels chuẩn hóa theo Lab 3 và **10** labels mặc định của GitHub được giữ nguyên, không xóa/ghi đè).

### 3.1. Nhóm Labels triển khai theo Lab 3 (18 labels)

| Nhóm | Label | Mã màu | Mô tả |
| :--- | :--- | :--- | :--- |
| Status | `status: new` | `#BFD4F2` | Công việc mới tạo, chưa bắt đầu thực hiện |
| Status | `status: in-progress` | `#FBCA04` | Công việc đang được triển khai |
| Status | `status: done` | `#0E8A16` | Công việc đã hoàn thành và được xác nhận |
| Story Point | `points: 0` | `#FEF2C0` | Story Point: 0 |
| Story Point | `points: 1` | `#F9D0C4` | Story Point: 1 |
| Story Point | `points: 3` | `#E99695` | Story Point: 3 (Product Backlog đề xuất) |
| Story Point | `points: 5` | `#F5C26B` | Story Point: 5 (Product Backlog đề xuất) |
| Story Point | `points: 7` | `#D9A026` | Story Point: 7 |
| Story Point | `points: 8` | `#E67E22` | Story Point: 8 (Product Backlog đề xuất) |
| Story Point | `points: 13` | `#B60205` | Story Point: 13 - Epic cần phân rã (Product Backlog đề xuất) |
| Thành viên | `member: phat` | `#D93F0B` | Phạm Minh Phát (GitHub: Salt05) |
| Thành viên | `member: cong` | `#5319E7` | Nguyễn Thành Công (chưa xác nhận GitHub username) |
| Loại công việc | `type: feature` | `#1D76DB` | Phát triển tính năng / User Story |
| Loại công việc | `type: bug` | `#D73A4A` | Lỗi phần mềm cần xử lý |
| Loại công việc | `type: fix` | `#E11D48` | Sửa lỗi / khắc phục sự cố |
| Loại công việc | `type: wontfix` | `#CFD3D7` | Không sửa / ngoài phạm vi xử lý |
| Loại công việc | `type: task` | `#006B75` | Công việc quản lý dự án, khởi động, Planning/Demo/Review/Retro |
| Loại công việc | `type: test` | `#7057FF` | Kiểm thử tích hợp, kiểm thử hồi quy và UAT |

> Ghi chú: Bổ sung `points: 5`, `points: 8`, `points: 13` để khớp thang điểm Planning Poker thực tế trong file thiết kế `Lab1_BanDienThoaiOnline (1) (2).xlsx`, và `type: task`, `type: test` cho các công việc quản lý/nghi thức và kiểm thử.

## 4. Tổng số Issues đã tạo

- **Tổng số Issues đã tạo:** **48** Issues (toàn bộ khởi tạo ở trạng thái `open` và gắn nhãn `status: new`).
  - Khởi động (Start-up): **2** Issues (`#1`–`#2`)
  - Sprint 1 – Foundation: **9** Issues (5 User Stories + 4 công việc quản lý/kiểm thử)
  - Sprint 2 – Shopping & Orders: **9** Issues (5 User Stories + 4 công việc quản lý/kiểm thử)
  - Sprint 3 – Administration: **9** Issues (5 User Stories + 4 công việc quản lý/kiểm thử)
  - Sprint 4 – Payment & Release R1: **7** Issues (3 User Stories + 4 công việc quản lý/UAT)
  - Release R2 – Backlog tương lai (chưa gắn Sprint): **12** Issues (`US19`–`US30`)

## 5. Danh sách Issues theo từng Sprint

### Khởi động (Start-up) (2 issues)

| Issue | Tiêu đề | Labels | GitHub Assignee | Link |
| :--- | :--- | :--- | :--- | :--- |
| #1 | [Startup] Tạo Project/Repository | `member: phat`, `status: new`, `type: task` | `Salt05` | [#1](https://github.com/Salt05/online-phone-store/issues/1) |
| #2 | [Startup] Thiết kế dữ liệu và hợp đồng API | `member: cong`, `status: new`, `type: task` | *(Chờ xác nhận username)* | [#2](https://github.com/Salt05/online-phone-store/issues/2) |

### Sprint 1 – Foundation (9 issues)

| Issue | Tiêu đề | Labels | GitHub Assignee | Link |
| :--- | :--- | :--- | :--- | :--- |
| #3 | [Sprint 1] Sprint Planning | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#3](https://github.com/Salt05/online-phone-store/issues/3) |
| #4 | [US01] Duyệt danh mục điện thoại | `member: cong`, `points: 3`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#4](https://github.com/Salt05/online-phone-store/issues/4) |
| #5 | [US02] Tìm kiếm và lọc sản phẩm | `member: cong`, `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#5](https://github.com/Salt05/online-phone-store/issues/5) |
| #6 | [US03] Chi tiết và lựa chọn SKU | `member: cong`, `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#6](https://github.com/Salt05/online-phone-store/issues/6) |
| #7 | [US04] Đăng ký bằng email | `member: phat`, `points: 5`, `status: new`, `type: feature` | `Salt05` | [#7](https://github.com/Salt05/online-phone-store/issues/7) |
| #8 | [US05] Đăng nhập và quản lý phiên | `member: phat`, `points: 5`, `status: new`, `type: feature` | `Salt05` | [#8](https://github.com/Salt05/online-phone-store/issues/8) |
| #9 | [Sprint 1] Kiểm thử tích hợp Sprint 1 (Integration / Sprint Testing) | `member: cong`, `member: phat`, `status: new`, `type: test` | `Salt05` | [#9](https://github.com/Salt05/online-phone-store/issues/9) |
| #10 | [Sprint 1] Demo Sprint 1 (Sprint Demo) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#10](https://github.com/Salt05/online-phone-store/issues/10) |
| #11 | [Sprint 1] Review và Retrospective Sprint 1 (Sprint Review & Retrospective) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#11](https://github.com/Salt05/online-phone-store/issues/11) |

### Sprint 2 – Shopping & Orders (9 issues)

| Issue | Tiêu đề | Labels | GitHub Assignee | Link |
| :--- | :--- | :--- | :--- | :--- |
| #12 | [Sprint 2] Sprint Planning | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#12](https://github.com/Salt05/online-phone-store/issues/12) |
| #13 | [US06] Quản lý giỏ theo SKU | `member: cong`, `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#13](https://github.com/Salt05/online-phone-store/issues/13) |
| #14 | [US07] Checkout và tạo đơn khách vãng lai | `member: cong`, `member: phat`, `points: 8`, `status: new`, `type: feature` | `Salt05` | [#14](https://github.com/Salt05/online-phone-store/issues/14) |
| #15 | [US08] Đặt đơn COD | `member: phat`, `points: 3`, `status: new`, `type: feature` | `Salt05` | [#15](https://github.com/Salt05/online-phone-store/issues/15) |
| #16 | [US09] Hồ sơ và địa chỉ giao hàng | `member: phat`, `points: 3`, `status: new`, `type: feature` | `Salt05` | [#16](https://github.com/Salt05/online-phone-store/issues/16) |
| #17 | [US10] Lịch sử đơn của khách hàng | `member: cong`, `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#17](https://github.com/Salt05/online-phone-store/issues/17) |
| #18 | [Sprint 2] Kiểm thử tích hợp Sprint 2 (Integration / Sprint Testing) | `member: cong`, `member: phat`, `status: new`, `type: test` | `Salt05` | [#18](https://github.com/Salt05/online-phone-store/issues/18) |
| #19 | [Sprint 2] Demo Sprint 2 (Sprint Demo) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#19](https://github.com/Salt05/online-phone-store/issues/19) |
| #20 | [Sprint 2] Review và Retrospective Sprint 2 (Sprint Review & Retrospective) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#20](https://github.com/Salt05/online-phone-store/issues/20) |

### Sprint 3 – Administration (9 issues)

| Issue | Tiêu đề | Labels | GitHub Assignee | Link |
| :--- | :--- | :--- | :--- | :--- |
| #21 | [Sprint 3] Sprint Planning | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#21](https://github.com/Salt05/online-phone-store/issues/21) |
| #22 | [US11] Phân quyền nhân sự vận hành | `member: cong`, `member: phat`, `points: 5`, `status: new`, `type: feature` | `Salt05` | [#22](https://github.com/Salt05/online-phone-store/issues/22) |
| #23 | [US12] Quản lý sản phẩm và tồn theo SKU | `member: cong`, `points: 8`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#23](https://github.com/Salt05/online-phone-store/issues/23) |
| #24 | [US13] Xử lý và giao đơn hàng | `member: phat`, `points: 8`, `status: new`, `type: feature` | `Salt05` | [#24](https://github.com/Salt05/online-phone-store/issues/24) |
| #25 | [US14] Quản lý trạng thái khách hàng | `member: phat`, `points: 3`, `status: new`, `type: feature` | `Salt05` | [#25](https://github.com/Salt05/online-phone-store/issues/25) |
| #26 | [US17] Tra cứu nhật ký thao tác quan trọng | `member: cong`, `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#26](https://github.com/Salt05/online-phone-store/issues/26) |
| #27 | [Sprint 3] Kiểm thử tích hợp Sprint 3 (Integration / Sprint Testing) | `member: cong`, `member: phat`, `status: new`, `type: test` | `Salt05` | [#27](https://github.com/Salt05/online-phone-store/issues/27) |
| #28 | [Sprint 3] Demo Sprint 3 (Sprint Demo) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#28](https://github.com/Salt05/online-phone-store/issues/28) |
| #29 | [Sprint 3] Review và Retrospective Sprint 3 (Sprint Review & Retrospective) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#29](https://github.com/Salt05/online-phone-store/issues/29) |

### Sprint 4 – Payment & Release R1 (7 issues)

| Issue | Tiêu đề | Labels | GitHub Assignee | Link |
| :--- | :--- | :--- | :--- | :--- |
| #30 | [Sprint 4] Sprint Planning | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#30](https://github.com/Salt05/online-phone-store/issues/30) |
| #31 | [US15] Thanh toán trực tuyến sandbox | `member: cong`, `member: phat`, `points: 8`, `status: new`, `type: feature` | `Salt05` | [#31](https://github.com/Salt05/online-phone-store/issues/31) |
| #32 | [US16] Hoàn thiện luồng mua trên mobile web | `member: cong`, `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#32](https://github.com/Salt05/online-phone-store/issues/32) |
| #33 | [US18] Bàn giao và khôi phục môi trường demo | `member: phat`, `points: 5`, `status: new`, `type: feature` | `Salt05` | [#33](https://github.com/Salt05/online-phone-store/issues/33) |
| #34 | [Sprint 4] Kiểm thử hồi quy và UAT cuối (Regression Testing & UAT) | `member: cong`, `member: phat`, `status: new`, `type: test` | `Salt05` | [#34](https://github.com/Salt05/online-phone-store/issues/34) |
| #35 | [Sprint 4] Demo Release R1 (Sprint Demo) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#35](https://github.com/Salt05/online-phone-store/issues/35) |
| #36 | [Sprint 4] Review, Retrospective và bàn giao (Sprint Review & Retrospective) | `member: cong`, `member: phat`, `status: new`, `type: task` | `Salt05` | [#36](https://github.com/Salt05/online-phone-store/issues/36) |

### Release R2 – Backlog tương lai (12 issues)

| Issue | Tiêu đề | Labels | GitHub Assignee | Link |
| :--- | :--- | :--- | :--- | :--- |
| #37 | [US19] Xác minh và khôi phục tài khoản | `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#37](https://github.com/Salt05/online-phone-store/issues/37) |
| #38 | [US20] Tra cứu đơn khách vãng lai | `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#38](https://github.com/Salt05/online-phone-store/issues/38) |
| #39 | [US21] Tích hợp đơn vị giao nhận | `points: 8`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#39](https://github.com/Salt05/online-phone-store/issues/39) |
| #40 | [US22] Tiếp nhận yêu cầu đổi trả | `points: 8`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#40](https://github.com/Salt05/online-phone-store/issues/40) |
| #41 | [US23] Hoàn tiền có phê duyệt | `points: 8`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#41](https://github.com/Salt05/online-phone-store/issues/41) |
| #42 | [US24] Đối soát thanh toán và COD | `points: 8`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#42](https://github.com/Salt05/online-phone-store/issues/42) |
| #43 | [US25] Quản lý nhiều kho và IMEI | `points: 13`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#43](https://github.com/Salt05/online-phone-store/issues/43) |
| #44 | [US26] Khuyến mại có điều kiện | `points: 8`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#44](https://github.com/Salt05/online-phone-store/issues/44) |
| #45 | [US27] Báo cáo doanh thu và vận hành | `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#45](https://github.com/Salt05/online-phone-store/issues/45) |
| #46 | [US28] Ứng dụng Android và iOS | `points: 13`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#46](https://github.com/Salt05/online-phone-store/issues/46) |
| #47 | [US29] Sẵn sàng vận hành production | `points: 13`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#47](https://github.com/Salt05/online-phone-store/issues/47) |
| #48 | [US30] Tra cứu bảo hành thiết bị | `points: 5`, `status: new`, `type: feature` | *(Chờ xác nhận username)* | [#48](https://github.com/Salt05/online-phone-store/issues/48) |

## 6. Phân công thành viên

| Thành viên | GitHub Username | Trạng thái truy cập Repo | Label | Công việc phụ trách chính | Công việc phối hợp 2 người |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Phạm Minh Phát** | `Salt05` | Owner (`admin`) — Đã assign trực tiếp | `member: phat` | Startup Repo (`#1`), `US04` (`#7`), `US05` (`#8`), `US08` (`#15`), `US09` (`#16`), `US13` (`#24`), `US14` (`#25`), `US18` (`#33`) | `US07` (`#14`), `US11` (`#22`), `US15` (`#31`) và các task Planning/Testing/Demo/Review/UAT của 4 Sprint |
| **Nguyễn Thành Công** | *Chưa xác nhận* | Chưa là collaborator — Chưa assign được trên GitHub | `member: cong` | Startup API/DB (`#2`), `US01` (`#4`), `US02` (`#5`), `US03` (`#6`), `US06` (`#13`), `US10` (`#17`), `US12` (`#23`), `US17` (`#26`), `US16` (`#32`) | `US07` (`#14`), `US11` (`#22`), `US15` (`#31`) và các task Planning/Testing/Demo/Review/UAT của 4 Sprint |

## 7. Cấu hình Git workflow

- **Quy ước nhánh:**
  - `main`: Nhánh ổn định, không phát triển code nghiệp vụ trực tiếp trên `main`.
  - `feature/USxx-name`: Nhánh phát triển User Story mới (ví dụ: `feature/US01-product-catalog`).
  - `fix/USxx-name`: Nhánh sửa lỗi phát sinh (ví dụ: `fix/US07-idempotency-key`).
- **Quy trình Pull Request:**
  1. Tạo nhánh riêng từ `main` cho từng Issue khi bắt đầu triển khai và cập nhật label `status: in-progress`.
  2. Tạo Pull Request kèm từ khóa liên kết Issue `Closes #ID` (đã cấu hình sẵn mẫu tại [`.github/PULL_REQUEST_TEMPLATE.md`](../../.github/PULL_REQUEST_TEMPLATE.md)).
  3. Thành viên còn lại thực hiện Code Review.
  4. Chỉ Merge vào `main` sau khi được Approve; chưa tạo PR giả khi chưa có thay đổi code thực tế.

## 8. GitHub Project Board

- **Trạng thái:** **Chưa tạo được tự động qua API** (xem chi tiết tại Mục 10).
- **Thiết kế Board chuẩn cần hoàn thiện trên giao diện GitHub Projects v2:**
  - Cột trạng thái: `Todo` (`status: new`), `In Progress` (`status: in-progress`), `Done` (`status: done`).
  - Liên kết toàn bộ 48 Issues vào Project và cấu hình các View theo dõi theo **Sprint (Milestone)**, **Assignee**, **Status**, **Story Point**.

## 9. Các chức năng quản lý tiến độ và Bộ lọc truy vấn (Saved Filters)

Có thể theo dõi tiến độ trực tiếp trên GitHub Issues thông qua các bộ lọc chuẩn sau:

| Mục đích theo dõi | Chuỗi truy vấn (Filter Query) | Link trực tiếp |
| :--- | :--- | :--- |
| Tất cả công việc Sprint 1 | `is:issue milestone:"Sprint 1 – Foundation"` | [Xem Sprint 1](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+milestone%3A%22Sprint+1+%E2%80%93+Foundation%22) |
| Tất cả công việc Sprint 2 | `is:issue milestone:"Sprint 2 – Shopping & Orders"` | [Xem Sprint 2](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+milestone%3A%22Sprint+2+%E2%80%93+Shopping+%26+Orders%22) |
| Tất cả công việc Sprint 3 | `is:issue milestone:"Sprint 3 – Administration"` | [Xem Sprint 3](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+milestone%3A%22Sprint+3+%E2%80%93+Administration%22) |
| Tất cả công việc Sprint 4 | `is:issue milestone:"Sprint 4 – Payment & Release R1"` | [Xem Sprint 4](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+milestone%3A%22Sprint+4+%E2%80%93+Payment+%26+Release+R1%22) |
| Công việc của Phạm Minh Phát | `is:issue is:open label:"member: phat"` | [Lọc Phát](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+is%3Aopen+label%3A%22member%3A+phat%22) |
| Công việc của Nguyễn Thành Công | `is:issue is:open label:"member: cong"` | [Lọc Công](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+is%3Aopen+label%3A%22member%3A+cong%22) |
| Công việc đang thực hiện | `is:issue is:open label:"status: in-progress"` | [Lọc In-Progress](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+is%3Aopen+label%3A%22status%3A+in-progress%22) |
| Công việc đã hoàn thành | `is:issue label:"status: done"` | [Lọc Done](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+label%3A%22status%3A+done%22) |
| Backlog tương lai (Release R2) | `is:issue is:open no:milestone` | [Lọc Backlog R2](https://github.com/Salt05/online-phone-store/issues?q=is%3Aissue+is%3Aopen+no%3Amilestone) |

### Quy trình cập nhật trạng thái & đóng Sprint (Phần 8)
- Khi tạo Issue: gắn `status: new`.
- Khi bắt đầu thực hiện: đổi sang `status: in-progress`.
- Khi hoàn thành và được xác nhận: đổi sang `status: done` và đóng Issue.
- Cuối Sprint: kiểm tra toàn bộ Issues, Pull Requests và các task chưa hoàn thành; tổng kết Sprint; chỉ đóng Milestone khi Sprint thực sự kết thúc và được xác nhận (không đóng chỉ vì đến deadline).

## 10. Các thao tác chưa hoàn thành, nguyên nhân và điểm cần xác nhận

### 10.1. Thao tác bị chặn bởi quyền / dữ liệu
1. **Tạo GitHub Project Board (Projects v2) và liên kết 48 Issues:**
   - **Nguyên nhân:** Token GitHub hiện tại chỉ có các scopes `gist, notifications, read:gpg_key, read:org, repo, user, workflow, write:public_key`, thiếu scope `project` (`read:project`, `write:project`). API GraphQL trả về lỗi `INSUFFICIENT_SCOPES`, còn REST API Classic Projects (`/projects`) đã bị GitHub ngừng hỗ trợ (`404 Not Found`).
   - **Cách khắc phục:** Cấp thêm scope `project` cho token hoặc tạo trực tiếp Project Board trên giao diện web GitHub và gắn 48 Issues vào cột `Todo`.
2. **Gán GitHub Assignee cho Nguyễn Thành Công và mời cộng tác viên:**
   - **Nguyên nhân:** Tài liệu dự án chưa ghi nhận GitHub username của Nguyễn Thành Công và danh sách collaborator hiện tại chỉ có `Salt05`.
   - **Cách khắc phục:** Cung cấp GitHub username của Nguyễn Thành Công, gửi lời mời collaborator (`Settings → Collaborators`), và sau khi chấp nhận thì assign vào các Issue mang nhãn `member: cong`.

### 10.2. Các điểm cần nhóm / giảng viên xác nhận thêm
1. **Người chịu trách nhiệm chính (Lead) cho các công việc 2 người:** `US07` (`#14`), `US11` (`#22`), `US15` (`#31`) và các task Sprint Planning / Testing / Demo / Review & Retrospective hiện đều ghi cả `Nguyễn Thành Công, Phạm Minh Phát` trong MS Project nhưng chưa phân rõ Lead và Co-owner.
2. **Story Point cho công việc quản lý / khởi động:** Các task ngoài User Story (`#1`–`#3`, `#9`–`#12`, `#18`–`#21`, `#27`–`#30`, `#34`–`#36`) chưa có Story Point trong bảng phân công nên chưa gán nhãn `points: *` (cần xác nhận có gán `points: 0` hay giữ nguyên không gán).
3. **Chênh lệch giờ ước lượng giữa MS Project và Excel Sprint Backlog:** `US13` (MS Project `37 hrs` vs Excel `41 hrs`) và `US17` (MS Project `5 hrs` vs Excel `26 hrs`).
4. **Planning Poker:** Toàn bộ điểm số `3, 5, 8, 13` trong Excel Product Backlog đang ở trạng thái *"Chờ Planning Poker"*.

## 11. Link trực tiếp đến các thành phần trên GitHub

- **Repository:** https://github.com/Salt05/online-phone-store
- **Issues:** https://github.com/Salt05/online-phone-store/issues
- **Labels:** https://github.com/Salt05/online-phone-store/labels
- **Milestones:** https://github.com/Salt05/online-phone-store/milestones
- **Pull Requests:** https://github.com/Salt05/online-phone-store/pulls
- **Projects (cần tạo/liên kết bổ sung):** https://github.com/Salt05/online-phone-store/projects

# Doctory Documentation Map

Tài liệu trong thư mục này được chia theo hai lớp:

1. Tài liệu tổng quan cấp dự án ở `docs/*.md`.
2. Tài liệu chuyên sâu theo mảng ở các thư mục con như `docs/design/` và `docs/patients/`.

## Nguồn chuẩn hiện tại

| Mảng | Nguồn chuẩn | Ghi chú |
|---|---|---|
| Tầm nhìn dự án | `00_PROJECT_VISION.md` | Hiện mới là placeholder. |
| GDD tổng hợp | `02_GAME_DESIGN_DOCUMENT.md` | Hiện mới là placeholder, sau này nên link tới các tài liệu chuyên sâu thay vì copy lại toàn bộ. |
| Core gameplay | `03_CORE_GAMEPLAY.md` | Hiện mới là placeholder. |
| Patient system tổng quan | `04_PATIENT_SYSTEM.md` | Hiện mới là placeholder. Không nên chứa từng case chi tiết. |
| Patient case chi tiết | `patients/` | Nguồn chuẩn cho inbox, template, index và từng case bệnh nhân. |
| Medical simulation | `07_MEDICAL_SIMULATION.md` | Hiện mới là placeholder. |
| MVP scope | `11_MVP_SCOPE.md` | Hiện mới là placeholder. |
| Open questions | `12_OPEN_QUESTIONS.md` | Hiện mới là placeholder. |
| Design principles | `design/DESIGN_PRINCIPLES.md` | Nguồn chuẩn cho nguyên tắc thiết kế đang được chốt. |
| Design decisions | `design/DESIGN_DECISION_LOG.md` | Nguồn chuẩn cho lịch sử quyết định. |
| Design philosophy | `99_DESIGN_PHILOSOPHY.md` | Hiện mới là placeholder. Sau này chỉ giữ triết lý dài hạn, không ghi quyết định cụ thể. |

## Quy tắc tránh trùng lặp

- File cấp dự án chỉ mô tả vai trò, phạm vi, quyết định chính và link tới tài liệu chuyên sâu.
- File trong thư mục chuyên sâu là nguồn chuẩn cho chi tiết của mảng đó.
- Không copy nguyên nội dung case bệnh nhân vào `04_PATIENT_SYSTEM.md` hoặc `02_GAME_DESIGN_DOCUMENT.md`.
- Không copy nguyên decision log vào `99_DESIGN_PHILOSOPHY.md`.
- Khi hai file nói về cùng một ý, một file phải được đánh dấu là nguồn chuẩn, file còn lại chỉ link tới nguồn chuẩn.

## Trạng thái tài liệu

| Nhóm | Trạng thái | Việc cần làm |
|---|---|---|
| Root docs `00`-`12`, `99` | Placeholder | Cần mở rộng dần hoặc biến thành index ngắn. |
| `docs/design/` | Có nội dung ban đầu | Cần giữ làm nguồn chuẩn cho nguyên tắc và quyết định. |
| `docs/patients/` | Có cấu trúc ban đầu | Cần phát triển case theo template, không trộn vào root docs. |


# Documentation Reorganization Plan

## Mục tiêu

Thống nhất hệ thống tài liệu Doctory để mỗi ý có đúng một nơi làm nguồn chuẩn, còn các file khác chỉ tóm tắt và trỏ link.

## Vấn đề hiện tại

1. Root docs `00`-`12` và `99` mới là placeholder nên chưa sai, nhưng tên file đã có khả năng chồng lên tài liệu chuyên sâu.
2. `04_PATIENT_SYSTEM.md` có thể trùng với `docs/patients/` nếu sau này copy case vào đó.
3. `99_DESIGN_PHILOSOPHY.md` có thể trùng với `docs/design/DESIGN_PRINCIPLES.md` nếu cả hai cùng ghi nguyên tắc thiết kế.
4. `02_GAME_DESIGN_DOCUMENT.md` có thể phình thành bản copy của mọi file nếu không đặt giới hạn.

## Quyết định sắp xếp

### 1. Giữ root docs làm lớp tổng quan

Root docs dùng để định hướng và liên kết:

- `00_PROJECT_VISION.md`: lý do tồn tại, promise, trụ cột sản phẩm.
- `02_GAME_DESIGN_DOCUMENT.md`: bản đồ GDD tổng hợp, không copy toàn bộ nội dung chuyên sâu.
- `03_CORE_GAMEPLAY.md`: loop, input chính, nhịp chơi.
- `04_PATIENT_SYSTEM.md`: luật tổng quan của hệ thống bệnh nhân.
- `07_MEDICAL_SIMULATION.md`: nguyên tắc mô phỏng y khoa giả tưởng.
- `11_MVP_SCOPE.md`: phạm vi build đầu tiên.
- `12_OPEN_QUESTIONS.md`: câu hỏi chưa chốt.
- `99_DESIGN_PHILOSOPHY.md`: triết lý dài hạn, không ghi quyết định triển khai cụ thể.

### 2. Giữ thư mục con làm nguồn chuẩn chi tiết

- `docs/design/`: nguyên tắc thiết kế và decision log.
- `docs/patients/`: dữ liệu, template, index và từng patient case.

### 3. Xử lý nội dung trùng trong tương lai

Nếu phát hiện hai file có cùng nội dung:

1. Chọn file nguồn chuẩn theo bảng trong `docs/README.md`.
2. Giữ nội dung đầy đủ ở file nguồn chuẩn.
3. Ở file còn lại, thay nội dung trùng bằng tóm tắt 2-5 dòng và link tới nguồn chuẩn.
4. Không xóa file chỉ vì trùng, trừ khi đã có quyết định rõ rằng file đó không còn vai trò.

## Các bước đề xuất

### Phase 1 - Chuẩn hóa khung tài liệu

- Thêm `docs/README.md` làm bản đồ tài liệu.
- Sửa các placeholder root docs để mỗi file có: purpose, source-of-truth links, out-of-scope.
- Cập nhật `12_OPEN_QUESTIONS.md` thành nơi gom câu hỏi thật.

### Phase 2 - Lấp nội dung ưu tiên

- Viết `00_PROJECT_VISION.md` trước.
- Viết `11_MVP_SCOPE.md` thứ hai.
- Viết `03_CORE_GAMEPLAY.md` và `04_PATIENT_SYSTEM.md` ở mức tổng quan.
- Giữ patient case chi tiết trong `docs/patients/cases/`.

### Phase 3 - Chống trùng khi tài liệu lớn dần

- Mỗi lần thêm docs mới, cập nhật `docs/README.md`.
- Nếu root doc cần nhắc tới chi tiết, dùng link thay vì copy.
- Nếu thay đổi quyết định thiết kế, ghi vào `docs/design/DESIGN_DECISION_LOG.md`.

## Việc không làm lúc này

- Không tạo Unity project.
- Không code gameplay.
- Không xóa hoặc rename tài liệu cũ.
- Không gộp toàn bộ docs vào một file lớn.


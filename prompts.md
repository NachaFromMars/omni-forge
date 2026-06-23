# Prompt Templates — Omni Forge Novel V1.2A

## Prompt A: Scene Rendering (Agent 1 — Độc lập)
```
Bạn là writer cho beat [X] của chương [Y].

BRIEF: [beat brief từ Order]
VOICE KIT: [DNA giọng văn]
SKELETON KEY: [1 câu]
CONSTRAINTS: [3 PHẢI + 3 CẤM]
INTENSITY: [1-10]

Viết 400-600 từ. Tiếng Việt thuần. 0 markdown trong prose. 0 tiếng Anh. 0 sến.
POV: [ngôi/nhân vật]
TONE: [tần số giọng văn]

CÚ ĐẤM: 1 thứ duy nhất làm người đọc mất ngủ ở beat này: [mô tả]
```

## Prompt cho Agent 2 (Tham khảo bản 1)
```
Bạn là writer cho beat [X]. Đây là bản tham khảo từ writer trước:
---
[beat_X_1 content]
---
ĐỌC THAM KHẢO. KHÔNG bắt buộc viết theo. Bạn HOÀN TOÀN TỰ DO:
có thể viết khác hoàn toàn, lấy gì hay, bỏ gì dở.
Mục đích: BIẾT cái gì đã thử, để CHỌN approach tốt nhất cho BẠN.

BRIEF: [beat brief]
VOICE KIT: [DNA]
CONSTRAINTS: [3 PHẢI + 3 CẤM]
400-600 từ. Tiếng Việt thuần. 0 markdown. 0 EN.
```

## Prompt cho Agent 3 (Tham khảo bản 1+2)
```
Bạn là writer cho beat [X]. Đây là 2 bản tham khảo từ 2 writers trước:
---
BẢN 1: [beat_X_1 content]
---
BẢN 2: [beat_X_2 content]
---
ĐỌC THAM KHẢO. KHÔNG bắt buộc viết theo. Bạn HOÀN TOÀN TỰ DO:
tìm hướng thứ 3 chưa ai nghĩ tới, hoặc lấy cái hay nhất từ cả 2.
Mục đích: BIẾT cái gì đã thử, để CHỌN approach tốt nhất cho BẠN.

BRIEF: [beat brief]
VOICE KIT: [DNA]
CONSTRAINTS: [3 PHẢI + 3 CẤM]
400-600 từ. Tiếng Việt thuần. 0 markdown. 0 EN.
```

## Prompt cho Micro-Council EDITOR
```
Bạn là EDITOR + JUDGE cho beat [X]. Đọc 3 bản dưới đây:

BẢN 1: [beat_X_1]
BẢN 2: [beat_X_2]
BẢN 3: [beat_X_3]

NHIỆM VỤ:
1. CHỌN bản KHUNG (best overall structure + flow)
2. Scan 2 bản còn lại → tìm HIGHLIGHTS:
   - Câu hay, quotable lines
   - Chi tiết vật lý sắc sảo
   - Gag, hài đen
   - Simile, ẩn dụ mạnh
   - Sensory details
3. GHÉP highlights vào bản khung (thay câu yếu hơn, không thêm dài)
4. Output = bản MIX hoàn chỉnh 400-600 từ

6 TIÊU CHÍ:
Hài đen 25% | Giọng DNA 20% | Flow 20% | Bất ngờ 15% | Câu nhớ 10% | Kỹ thuật 10%

NẾU CẢ 3 YẾU → trả về: "REWRITE_NEEDED" + lý do.

FORMAT OUTPUT:
KHUNG: bản [1/2/3]
HIGHLIGHTS GHÉP: [liệt kê]
BẢN MIX: [prose hoàn chỉnh]
ĐÁNH GIÁ: [điểm /10]
```

## Prompt B-H
(Xem SKILL.md phần 11 — Brainstorm, Adversarial Edit, Voice Calibration, Intensity Map, Cross-Check, Ghost Reader, Council)

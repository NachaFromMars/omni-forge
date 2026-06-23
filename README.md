# Omni Forge Novel V1.2A

**Hệ thống rèn AI viết tiểu thuyết — Sequential Competition + Mix Edition**

> "Token rẻ hơn tác phẩm tệ. Luôn chọn chất lượng."

## Tổng Quan

Omni Forge Novel là hệ thống hoàn chỉnh để rèn AI viết tiểu thuyết — từ ý tưởng thô đến bản thảo sẵn sàng xuất bản.

### V1.2A — Nâng cấp lõi:
- **3 agents viết TUẦN TỰ** — agent sau đọc bản trước tham khảo nhưng hoàn toàn tự do
- **Micro-council = EDITOR + JUDGE** — chọn bản khung + MIX highlights từ tất cả bản
- **Chất lượng = MIX(BEST_OF_3)** — không lãng phí bất kỳ câu hay nào

### Tính năng:
- FORGE+C 2.0 (8 bước sản xuất)
- OIF Infinity Loop (6 phases)
- Hội đồng Nacharium (5 vai nhanh / 13 personas đầy đủ)
- 3-Agent Sequential Competition Micro-Beat (400-600 từ/beat)
- 12 kỹ thuật cấp cao
- 738 kỹ thuật văn học
- 96 yếu tố văn học
- 8 prompt templates (bao gồm Agent 2, Agent 3, EDITOR prompts)
- Chẩn đoán 16 bệnh văn chương
- 14 lệnh tắt + 5 lệnh OIF
- Fault tolerance + Self-absorption evolution

## Cài Đặt

### Cách 1: ClawHub (khuyến nghị)
```bash
clawhub install omni-forge-novel
```

### Cách 2: Thủ công
1. Copy thư mục `omni-forge-novel-v1.2a/` vào `skills/omni-forge/` trong workspace
2. Hoặc paste nội dung `SKILL.md` vào đầu phiên chat với bất kỳ AI nào

### Cách 3: Dùng trực tiếp
Paste toàn bộ nội dung `SKILL.md` vào system prompt hoặc đầu conversation.

## Tương Thích

Áp dụng cho mọi LLM:
- Claude (Opus, Sonnet, Haiku)
- GPT-4, GPT-4o
- Gemini Pro, Ultra
- Qwen
- Mistral
- Và mọi LLM khác

## Quick Start

### Bước 1: Chuẩn bị Voice Kit
300-500 từ prose mẫu + tag giải thích. Paste đầu phiên.

### Bước 2: Frame chương
Skeleton Key + 3 PHẢI/3 CẤM + micro-outline 5 beats

### Bước 3: Chạy FORGE+C 2.0 + Sequential 3-Agent + MIX
```
F → O → R(×3 tuần tự + micro-council EDITOR MIX) → G → E → C → +C
```

## Token Budget

| | V1.0 | V1.1A | V1.2A |
|---|---|---|---|
| Tổng calls | ~9 | ~26 | ~26 |
| Token | ~3-5M | ~8-12M | ~12-16M |
| Thời gian | ~15 phút | ~40 phút | ~60 phút |
| Chất lượng | Tốt | MAX(3) | **MIX(BEST_OF_3)** |

## Evolution

```
V1.0 (1-agent) → V1.1 (3-agent song song) → V1.1A (bỏ label, tách bước)
→ V1.2 (tuần tự + MIX) → V1.2A (tự do + EDITOR mode)
```

## Credits

- **Mr Nấng / Nacharium** — Tác giả hệ thống
- **Tiểu Tâm** — AI assistant, đúc V1.0
- **La MulaPC1** — AI assistant, đúc V1.1A, V1.2A

## License

MIT License — Sử dụng tự do, ghi credit nếu chia sẻ.

---

*"Token rẻ hơn tác phẩm tệ. Luôn chọn chất lượng."*

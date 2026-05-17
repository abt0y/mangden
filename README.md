---
created: 2026-05-17T11:10
updated: 2026-05-17T11:10
---
# Báo cáo Thực trạng Giáo dục Đặc biệt
## Trường Tiểu học Quang Trung – Điểm Chuyên biệt TTCTXH Kon Tum
### Dự án Inclusion 2b | MDT Integrated Rehabilitation Model

---

## Giới thiệu

Repository này lưu trữ toàn bộ tài liệu, dữ liệu, công cụ và tài liệu tham
khảo cho **Báo cáo Thực trạng GDĐB** được thực hiện tháng 5/2026 trong khuôn
khổ **Dự án Inclusion 2b** – hỗ trợ người khuyết tật bị ảnh hưởng chất độc
da cam/dioxin tại tỉnh Kon Tum.

**Chuyên gia thực hiện:** Lê Tuấn Đức – Giáo dục Đặc biệt & PHCN Liên ngành  
**Đơn vị:** Trường TH Quang Trung, Phường Đắk Cấm – Điểm CB tại TTCTXH Kon Tum  
**Mô hình hướng đến:** One PWD = One IIP (MDT Integrated Rehabilitation)

---

## Cấu trúc thư mục

| Thư mục | Nội dung |
|---|---|
| `reports/current/` | Báo cáo nâng cấp hoàn chỉnh (phiên bản mới nhất) |
| `reports/archive/` | Báo cáo gốc và các phiên bản cũ |
| `references/` | Tài liệu tham khảo: WHO, luật VN, quốc tế |
| `data/` | Hồ sơ chức năng học sinh, ghi chú phỏng vấn |
| `tools/` | Mẫu IIP, biểu mẫu đánh giá, danh mục học liệu |
| `presentations/` | Slide tập huấn và hội thảo |
| `scripts/` | Script tạo file báo cáo (.docx) |

---

## Tài liệu chính

📄 **Báo cáo nâng cấp (v2.0):**  
`reports/current/BaoCao_NangCap_GDDB_QuangTrung_KonTum_2026.docx`

Báo cáo ~18.000 từ, 15 chương, 20+ bảng biểu, bao gồm:
- Executive Summary toàn diện
- Phân tích 8 ca điển hình theo khung ICF-CY
- So sánh IEP cũ vs IIP tích hợp MDT
- 10 mục tiêu SMART cụ thể theo từng dạng tật
- Chiến lược can thiệp: AAC/PECS, PBS/FBA, ADL Task Analysis
- Lộ trình tập huấn 24 tháng
- Danh mục 25 loại học liệu có giá ước tính
- Kế hoạch hành động + Ma trận RACI + KPI
- Khuyến nghị chính sách
- 25 tài liệu tham khảo khoa học

---

## Mã ICF được sử dụng

| Mã | Lĩnh vực | Ghi chú |
|---|---|---|
| d310–d399 | Giao tiếp (Communication) | Tiếp nhận & diễn đạt |
| d410–d499 | Vận động (Mobility) | Tư thế, di chuyển, vận động tinh |
| d510–d599 | Tự chăm sóc (Self-care / ADL) | Vệ sinh, ăn uống, mặc quần áo |
| b117 | Chức năng trí tuệ (Intellectual functions) | Đánh giá KTTT |
| b140 | Chức năng chú ý (Attention functions) | Đánh giá ADHD |

Nguồn: WHO ICF 2026-01 — https://icd.who.int/browse/2026-01/icf/en

---

## Tái tạo báo cáo

```bash
# Yêu cầu: Node.js + thư viện docx
npm install -g docx
node scripts/generate_report.js
# Output: BaoCao_NangCap_GDDB_QuangTrung_KonTum_2026.docx
```

---

## Tài liệu tham khảo chính

- WHO (2007). ICF-CY. Geneva: WHO Press. [PDF](https://apps.who.int/iris/bitstream/10665/43737/1/9789241547321_eng.pdf)
- WHO (2026). ICF Release 2026-01. [Browser](https://icd.who.int/browse/2026-01/icf/en)
- Vygotsky (1978). Mind in Society. Harvard University Press.
- Bronfenbrenner (1979). The Ecology of Human Development. Harvard University Press.
- Cooper et al. (2020). Applied Behavior Analysis (3rd ed.). Pearson.
- Bondy & Frost (2001). The Picture Exchange Communication System. *Behavior Modification*, 25(5).
- CAST (2018). UDL Guidelines v2.2. [udlguidelines.cast.org](http://udlguidelines.cast.org)
- Bộ GD&ĐT (2023). Thông tư 27/2023/TT-BGDĐT.

Xem đầy đủ 25 tài liệu tham khảo: `references/citations.bib`

---

## Liên hệ

Dự án Inclusion 2b | Kon Tum, Việt Nam  
Tháng 5 năm 2026

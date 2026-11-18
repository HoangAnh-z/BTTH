## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```JSON
[
  {"ma_goi": "SVT", "ngay_su_kien": "2026-12-20", "nguoi_lon": 2, "tre_em": 1, "loai_ve": "thuong", "ghi_chu": null},
  {"ma_goi": "FZ", "ngay_su_kien": "2027-01-05", "nguoi_lon": 3, "tre_em": 0, "loai_ve": "thuong", "ghi_chu": "một người cần hỗ trợ xe lăn"},
  {"ma_goi": "VIP", "ngay_su_kien": null, "nguoi_lon": 4, "tre_em": 0, "loai_ve": "vip", "ghi_chu": "một người khiếm thị cần hỗ trợ tìm chỗ"}
]
```

**Link trò chuyện:** https://claude.ai/share/4b62588c-65f0-42a9-8bf5-1285aa81fa1d


## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền người lớn: 5 × 1.200.000 = 6.000.000
Tiền trẻ em:
    Giá mỗi trẻ 5-11 tuổi: 1.200.000 × 70% = 840.000
    2 trẻ (8 và 10 tuổi): 2 × 840.000 = 1.680.000
    Bé 3 tuổi miễn phí: 0
Tiền vé: 6.000.000 + 1.680.000 = 7.680.000
Giảm giá nhóm: có 5 người lớn nên được giảm 5%.
Số tiền giảm: 7.680.000 × 5% = 384.000
Tiền vé sau giảm: 7.680.000 − 384.000 = 7.296.000
Phụ thu: 1 × 300.000 = 300.000 (không giảm)
Tổng tiền: 7.296.000 + 300.000 = 7.596.000
[RESULT: 7.596.000 đồng]

```

**Link trò chuyện:** https://claude.ai/share/3b3d0c2f-b727-46cb-9b79-eb051799d2bb

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```JSON
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_hiep_bi_anh_huong": 2,
  "tom_tat": "Khán giả gói SVT bị xếp sang khu không mái trong 2 hiệp đầu, trời mưa, ghế ướt."
}
```

**Link trò chuyện:** https://claude.ai/share/53eba864-3cd4-45e4-b334-28f13ea850d6

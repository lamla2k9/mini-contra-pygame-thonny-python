# 🎮 Mini Contra - Pygame Edition

Chào mừng bạn đến với dự án **Mini Contra**, một tựa game nhập vai hành động bắn súng màn hình ngang (Side-scrolling Platformer) được phát triển hoàn toàn bằng ngôn ngữ **Python** và thư viện **Pygame**. 

Dự án này là một sản phẩm giải trí mã nguồn mở, mô phỏng lại lối chơi huyền thoại của tựa game Contra cổ điển kết hợp với nhiều cơ chế hiện đại như hệ thống cuộn camera mượt mà, khắc chế quái cầm khiên, và cửa hàng nâng cấp vũ khí.

---

## ✨ Tính Năng Nổi Bật

*   **Scrolling Map (Bản đồ cuộn):** Bản đồ jungle dài 5000px giúp người chơi trải nghiệm cảm giác di chuyển liên tục tiến về phía trước.
*   **Hệ thống kẻ địch đa dạng:**
    *   *Lính thường:* Di chuyển và xả đạn cơ bản.
    *   *Sniper:* Bắn tỉa tầm xa với sát thương lớn.
    *   *Suicide Bomber:* Quái ôm bom cảm tử, tự phát nổ khi tiếp cận người chơi.
    *   *Shield Sniper:* Lính cầm khiên chống đạn, chặn không cho người chơi đi xuyên qua trừ khi bị tiêu diệt.
*   **Trùm cuối (Along Core Boss):** Cyborg khổng lồ ở cuối bản đồ với 3 cơ chế tấn công ngẫu nhiên bao gồm bắn đạn chùm, triệu hồi quái vật và quét tia laser hủy diệt gây rung lắc màn hình.
*   **Cửa hàng vũ khí (Weapons Store):** Sử dụng điểm (tiền) tích lũy khi diệt quái để mua Potion hồi máu, súng sấy liên thanh M4A1 hoặc Shotgun bắn chùm xuyên giáp.
*   **Hiệu ứng hình ảnh & Âm thanh:** Tích hợp hạt bụi (dust particles) khi di chuyển/tiếp đất, hiệu ứng nổ lan, rung màn hình (screen shake) và hệ thống âm thanh SFX/nhạc nền sống động.

---

## 🕹️ Hướng Dẫn Điều Khiển

| Phím bấm | Hành động |
| :--- | :--- |
| **`A` / `D`** hoặc **Mũi tên Trái / Phải** | Di chuyển sang trái / phải (Cuộn màn hình) |
| **`W`** hoặc **Mũi tên Lên** | Nhảy lên (Có hiệu ứng khói bụi tiếp đất) |
| **`SPACE` (Phím cách)** | Bắn đạn (Ghim chặt để sấy liên thanh nếu dùng M4A1) |
| **`E`** | Ném bom công phá diện rộng (Giới hạn số lượng) |
| **`B`** | Mở / Đóng cửa hàng mua súng và vật phẩm |
| **`ENTER`** | Xác nhận chọn menu / Mua đồ trong shop |
| **`ESC`** | Thoát nhanh game khi đã phá đảo hoặc trong menu |

---

## 🚀 Hướng Dẫn Cài Đặt & Chạy Game

Để chạy được tựa game này trên máy tính, bạn cần cài đặt sẵn **Python** (phiên bản 3.x trở lên).

### Bước 1: Tải mã nguồn
Bạn có thể tải file `.zip` của kho lưu trữ này về rồi giải nén, hoặc sử dụng lệnh `git clone` (nếu biết dùng Git):
```bash
git clone [https://github.com/THAY_THE_TEN_USER_GITHUB_CUA_BAN/mini-contra-pygame.git](https://github.com/THAY_THE_TEN_USER_GITHUB_CUA_BAN/mini-contra-pygame.git)
cd mini-contra-pygame

# 🎮 Obsidian Reward Hub

**Một trải nghiệm ghi chú được gamification với XP, levels và thông báo ngày đặc biệt**

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/sonct988/obsidian-reward-hub)
[![Obsidian](https://img.shields.io/badge/obsidian-0.15.0+-purple.svg)](https://obsidian.md)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## 🌟 Tổng Quan

Obsidian Reward Hub biến việc ghi chú của bạn thành một cuộc phiêu lưu thú vị! Plugin này thêm hệ thống gamification hoàn chỉnh vào Obsidian, giúp bạn duy trì động lực và tạo thói quen ghi chú tốt thông qua:

- 🏆 **Hệ thống XP và Level** - Kiếm điểm từ mỗi hoạt động
- 🎊 **Thông báo ngày đặc biệt** - Ăn mừng các dịp quan trọng
- 🎁 **Phần thưởng Review** - Khuyến khích xem lại ghi chú cũ
- 🎨 **Tùy chỉnh hoàn toàn** - Cá nhân hóa trải nghiệm của bạn

## 🚀 Tính Năng Chính

### 🎮 Hệ Thống Gamification

#### 📊 XP và Leveling
- **Công thức Level**: `Level = floor(sqrt(XP/100)) + 1`
- **Hiển thị Status Bar**: Thông tin real-time về level, XP và tiến độ
- **Level Up Celebrations**: Popup đặc biệt cho các mốc level quan trọng

#### ⭐ Cách Kiếm XP

| Hoạt Động | XP Nhận Được | Mô Tả |
|-----------|--------------|--------|
| 🔤 Gõ phím liên tục | +1 XP | Khuyến khích viết nhiều |
| ✏️ Chỉnh sửa ghi chú | +2 XP | Cải thiện nội dung |
| 👀 Xem ghi chú cũ | +6 XP* | Review kiến thức |
| 🔄 Sửa ghi chú cũ | +10 XP* | Cập nhật thông tin |
| 🎁 Bonus thủ công | Tùy chỉnh | Phần thưởng đặc biệt |

*_Áp dụng hệ số nhân cho ghi chú cũ hơn 7 ngày_

### 🎊 Hệ Thống Ngày Đặc Biệt

#### 📅 Ngày Được Cấu Hình Sẵn
- **🎉 Tết Dương Lịch** (01-01) - "Chúc mừng năm mới! Hãy tiếp tục hành trình ghi chú! 🎊"
- **❤️ Valentine** (02-14) - "Happy Valentine's Day! Tình yêu với việc ghi chú! ❤️"
- **🌸 Ngày Quốc Tế Phụ Nữ** (03-08) - "Chúc mừng ngày Quốc tế Phụ nữ! 🌸"
- **🇻🇳 Quốc Khánh Việt Nam** (09-02) - "Chúc mừng Quốc khánh Việt Nam! 🇻🇳"
- **🎄 Giáng Sinh** (12-25) - "Merry Christmas! Giáng sinh an lành! 🎄🎅"

#### 🛠️ Quản Lý Tùy Chỉnh
- ➕ Thêm ngày đặc biệt mới
- ✏️ Chỉnh sửa thông điệp và hình ảnh
- 🔧 Bật/tắt từng ngày riêng lẻ
- 🗑️ Xóa ngày không cần thiết

### 🛠️ Công Cụ Debug & Test

#### 🧪 Testing Suite
- **Quick Tests**: Test nhanh Level Up và Special Date
- **Custom Debug Notifications**: Tạo và quản lý thông báo test
- **Preview Function**: Xem trước thông báo trước khi lưu

```javascript
// Ví dụ debug notification
{
  id: "test-birthday",
  name: "Test Birthday",
  message: "Chúc mừng sinh nhật! 🎂🎉",
  imagePath: "https://example.com/birthday.jpg"
}
```

### ⚙️ Cài Đặt Nâng Cao

#### 🎚️ Tùy Chỉnh Hành Vi
- **Review XP Multiplier**: 1-5x (mặc định 2x)
- **Show Notifications**: Bật/tắt thông báo level up
- **Custom Level Messages**: Thông điệp cá nhân cho level đặc biệt
- **Custom Level Images**: Hình ảnh ăn mừng cho mốc level

#### 📊 Quản Lý Tiến Độ
- **Progress Tracking**: Theo dõi XP và level hiện tại
- **Reset Function**: Đặt lại tiến độ về 0
- **Detailed Statistics**: Xem thống kê chi tiết

## 🎯 Commands Có Sẵn

Truy cập thông qua Command Palette (`Ctrl/Cmd + P`):

- **🔍 Show Reward Hub Information**: Hiển thị thống kê chi tiết
- **🎁 Add Bonus XP**: Thêm XP thủ công cho debug hoặc thưởng đặc biệt
- **🧪 Debug/Test Notifications**: Mở công cụ test và debug

## 🎨 Giao Diện & Trải Nghiệm

### 🎭 Modal Interfaces
- **Welcome Modal**: Chào mừng người dùng mới với hướng dẫn đầy đủ
- **Level Up Modal**: Ăn mừng milestone với hiệu ứng đặc biệt
- **Special Date Modal**: Thông báo ngày đặc biệt với thông điệp tùy chỉnh
- **Info Modal**: Thống kê chi tiết với progress bar

### 🎨 Visual Elements
```css
/* Ví dụ styling cho progress bar */
.progress-bar {
  background: linear-gradient(90deg, #4CAF50, #8BC34A);
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}
```

## 📱 Tương Thích

- ✅ **Obsidian**: 0.15.0+
- ✅ **Desktop**: Windows, macOS, Linux
- ✅ **Mobile**: iOS, Android
- ✅ **Language**: Tiếng Việt hoàn toàn

## 🔧 Cài Đặt

### 📦 Từ Community Plugins
1. Mở Obsidian Settings
2. Đi tới Community Plugins
3. Tìm kiếm "Reward Hub"
4. Cài đặt và kích hoạt

### 🛠️ Manual Installation
1. Download file `main.js`, `manifest.json`, `styles.css`
2. Tạo folder `obsidian-reward-hub` trong `.obsidian/plugins/`
3. Copy files vào folder
4. Reload Obsidian và kích hoạt plugin

## 💡 Mẹo Sử Dụng

### 🏆 Tối Ưu Hóa XP
- **Thường xuyên review**: Ghi chú cũ cho XP cao hơn
- **Cập nhật liên tục**: Giữ ghi chú luôn được cải thiện
- **Sử dụng bonus**: Thưởng bản thân khi hoàn thành mục tiêu

### 🎯 Custom Level Messages
```javascript
// Ví dụ custom level
Level 50: "🎉 Nửa thế kỷ kiến thức! Bạn đã trở thành chuyên gia ghi chú! 🧠✨"
Level 100: "🏆 LEGEND! 100 levels - Bạn là bậc thầy của Obsidian! 👑"
```

## 🤝 Đóng Góp

Chúng tôi hoan nghênh mọi đóng góp! Xem [CONTRIBUTING.md](CONTRIBUTING.md) để biết thêm chi tiết.

### 🐛 Báo Lỗi
- Tạo [GitHub Issue](https://github.com/sonct988/obsidian-reward-hub/issues)
- Mô tả chi tiết lỗi và cách tái tạo
- Kèm theo screenshots nếu có

### 💡 Đề Xuất Tính Năng
- Mở [Feature Request](https://github.com/sonct988/obsidian-reward-hub/issues)
- Giải thích tại sao tính năng này hữu ích
- Mô tả implementation suggestions

## 📝 License

Dự án này được cấp phép theo [MIT License](LICENSE).

## 👨‍💻 Tác Giả

**sonct988**
- GitHub: [@sonct988](https://github.com/sonct988)

---

### 🙏 Lời Cảm Ơn

Cảm ơn cộng đồng Obsidian đã tạo nên một platform tuyệt vời cho việc quản lý kiến thức!

**🚀 Hãy bắt đầu hành trình gamification ghi chú của bạn ngay hôm nay!**

---

*Được tạo với ❤️ bởi sonct988 - Making knowledge management fun and rewarding!*

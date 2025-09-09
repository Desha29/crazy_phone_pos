# 📱 crazy_phone_pos
Local POS System for Mobile Store (Flutter Desktop)

**Crazy Phone POS** is a local Point of Sale (POS) system built with Flutter Desktop for mobile phone stores.  
It helps manage sales, scan barcodes, track stock, and send local notifications when products run low.  
Works 100% offline with local database support. 🚀  

---

## 🚀 Features
- 🛒 **Sales Screen** with barcode/QR scanner support  
- 📦 **Product Management** (add, edit, delete, stock control)  
- 🔔 **Local Notifications** when stock is low  
- 📊 **Reports** for daily/monthly sales  
- 💻 Desktop support: Windows / macOS / Linux  

---

## 🏗️ Project Structure
```
lib/
 ├── core/          # helpers, theme, widgets
 ├── features/
 │    ├── sales/    # cashier screen
 │    ├── products/ # product management
 │    ├── reports/  # reports & statistics
 │    ├── alerts/   # stock alerts & notifications
 ├── data/
 │    ├── models/   # Product, Invoice models
 │    ├── local_db/ # SQLite or Hive helper
 ├── main.dart
```

---

## 🛠️ Tech Stack
- **Flutter Desktop**  
- **SQLite / Hive** (local database)  
- **flutter_local_notifications** (stock alerts)  
- **Barcode Scanner Support** (works as keyboard input)  

---

## 🔧 Getting Started
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/crazy_phone_pos.git

# Enter the project directory
cd crazy_phone_pos

# Run the app on desktop
flutter run -d windows   # or macos/linux
```

---

## 📌 Roadmap
- [x] Project setup  
- [ ] Product management module  
- [ ] Sales screen with barcode scan  
- [ ] Stock alerts & local notifications  
- [ ] Reports & statistics dashboard  

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License
This project is licensed under the MIT License.

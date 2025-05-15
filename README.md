# 🛍️ Dukan Hisab Kitab - Yasin Ullah | 🛍️ دکان حساب کتاب - یاسین اللہ

A comprehensive, client-side shop accounting application built with HTML, CSS, and JavaScript, using IndexedDB for local data storage. All data stays on your device, ensuring privacy and offline access.
|
ایک جامع، کلائنٹ سائڈ شاپ اکاؤنٹنگ ایپلی کیشن جو HTML، CSS، اور JavaScript کے ساتھ بنائی گئی ہے، مقامی ڈیٹا اسٹوریج کے لیے IndexedDB کا استعمال کرتی ہے۔ تمام ڈیٹا آپ کے ڈیوائس پر رہتا ہے، پرائیویسی اور آف لائن رسائی کو یقینی بناتا ہے۔

---

## 📸 Screenshots | 📸 اسکرین شاٹس

<table>
  <tr>
    <td><img src="pic (1).png" alt="Dashboard Screenshot | ڈیش بورڈ اسکرین شاٹ" width="300"/></td>
    <td><img src="pic (2).png" alt="Sales Management Screenshot | سیلز مینجمنٹ اسکرین شاٹ" width="300"/></td>
    <td><img src="pic (3).png" alt="Product Management Screenshot | پروڈکٹ مینجمنٹ اسکرین شاٹ" width="300"/></td>
  </tr>
  <tr>
    <td><img src="pic (4).png" alt="Reports Screenshot | رپورٹس اسکرین شاٹ" width="300"/></td>
    <td><img src="pic (5).png" alt="Screenshot 5" width="300"/></td>
    <td><img src="pic (6).png" alt="Screenshot 6" width="300"/></td>
  </tr>
  <tr>
    <td><img src="pic (7).png" alt="Screenshot 7" width="300"/></td>
    <td><img src="pic (8).png" alt="Screenshot 8" width="300"/></td>
    <td><img src="pic (9).png" alt="Screenshot 9" width="300"/></td>
  </tr>
  <tr>
    <td><img src="pic (10).png" alt="Screenshot 10" width="300"/></td>
    <td><img src="pic (11).png" alt="Screenshot 11" width="300"/></td>
    <td><img src="pic (12).png" alt="Screenshot 12" width="300"/></td>
   
  </tr>
</table>

---

## ✨ Key Features | ✨ اہم خصوصیات

*   📊 **Dashboard Overview** | 📊 **ڈیش بورڈ کا جائزہ**:
    *   <i class="fas fa-chart-line"></i> Today's Total Income & Expenses | <i class="fas fa-chart-line"></i> آج کی کل آمدنی اور اخراجات
    *   <i class="fas fa-boxes"></i> Total Products Count | <i class="fas fa-boxes"></i> کل مصنوعات کی تعداد
    *   <i class="fas fa-hand-holding-usd"></i> Total Receivables from Customers | <i class="fas fa-hand-holding-usd"></i> صارفین سے کل قابل وصولی
    *   <i class="fas fa-file-invoice-dollar"></i> Total Payables to Suppliers | <i class="fas fa-file-invoice-dollar"></i> سپلائرز کو کل قابل ادائیگی
    *   <i class="fas fa-percentage"></i> Overall Profit/Loss (Last 30 Days) | <i class="fas fa-percentage"></i> مجموعی منافع/نقصان (گزشتہ 30 دن)

*   💰 **Income Management** | 💰 **آمدنی کا انتظام**:
    *   <i class="fas fa-cash-register"></i> Record Sales with item details, customer, payment method | <i class="fas fa-cash-register"></i> آئٹم کی تفصیلات، صارف، ادائیگی کے طریقے کے ساتھ سیلز ریکارڈ کریں
    *   <i class="fas fa-plus-circle"></i> Record Other Incomes (e.g., commission, rent) | <i class="fas fa-plus-circle"></i> دیگر آمدنی ریکارڈ کریں (مثلاً کمیشن، کرایہ)

*   🧾 **Expense Management** | 🧾 **اخراجات کا انتظام**:
    *   <i class="fas fa-money-bill-wave"></i> Log daily expenses with category, description, amount, payment method | <i class="fas fa-money-bill-wave"></i> زمرہ، تفصیل، رقم، ادائیگی کے طریقے کے ساتھ روزانہ اخراجات لاگ کریں

*   📦 **Product/Inventory Management** | 📦 **مصنوعات/انوینٹری کا انتظام**:
    *   <i class="fas fa-plus-square"></i> Add, Edit, Delete products | <i class="fas fa-plus-square"></i> مصنوعات شامل کریں، ترمیم کریں، حذف کریں
    *   <i class="fas fa-cubes"></i> Track stock levels (auto-updated with sales/purchases) | <i class="fas fa-cubes"></i> اسٹاک کی سطحوں کو ٹریک کریں (سیلز/خریداریوں کے ساتھ خودکار طور پر اپ ڈیٹ)
    *   <i class="fas fa-search"></i> Search and filter products | <i class="fas fa-search"></i> مصنوعات تلاش اور فلٹر کریں

*   👥 **Customer Management** | 👥 **صارفین کا انتظام**:
    *   <i class="fas fa-user-plus"></i> Add, Edit, Delete customers | <i class="fas fa-user-plus"></i> صارفین شامل کریں، ترمیم کریں، حذف کریں
    *   <i class="fas fa-balance-scale-right"></i> Maintain customer balances (receivables) | <i class="fas fa-balance-scale-right"></i> صارف کے بیلنس (قابل وصولی) کو برقرار رکھیں
    *   <i class="fas fa-handshake"></i> Record payments received | <i class="fas fa-handshake"></i> موصول شدہ ادائیگیوں کو ریکارڈ کریں

*   🚚 **Supplier Management** | 🚚 **سپلائرز کا انتظام**:
    *   <i class="fas fa-user-tie"></i> Add, Edit, Delete suppliers | <i class="fas fa-user-tie"></i> سپلائرز شامل کریں، ترمیم کریں، حذف کریں
    *   <i class="fas fa-balance-scale-left"></i> Maintain supplier balances (payables) | <i class="fas fa-balance-scale-left"></i> سپلائر کے بیلنس (قابل ادائیگی) کو برقرار رکھیں
    *   <i class="far fa-credit-card"></i> Record payments made | <i class="far fa-credit-card"></i> کی گئی ادائیگیوں کو ریکارڈ کریں

*   📚 **Running Khatas (Ledgers)** | 📚 **چلتے کھاتے (لیجرز)**:
    *   <i class="fas fa-book"></i> Detailed transaction history for products, customers, suppliers, and overall finances. | <i class="fas fa-book"></i> مصنوعات، صارفین، سپلائرز، اور مجموعی مالیات کے لیے تفصیلی ٹرانزیکشن ہسٹری۔

*   📄 **Reporting** | 📄 **رپورٹنگ**:
    *   <i class="fas fa-calendar-day"></i> Day Book | <i class="fas fa-calendar-day"></i> روزنامچہ (ڈے بک)
    *   <i class="fas fa-user-friends"></i> Customer Ledger | <i class="fas fa-user-friends"></i> صارف کا کھاتہ
    *   <i class="fas fa-parachute-box"></i> Supplier Ledger | <i class="fas fa-parachute-box"></i> سپلائر کا کھاتہ
    *   <i class="fas fa-boxes"></i> Product Stock Ledger | <i class="fas fa-boxes"></i> پروڈکٹ اسٹاک کھاتہ
    *   <i class="fas fa-file-invoice"></i> Expense Report | <i class="fas fa-file-invoice"></i> اخراجات کی رپورٹ
    *   <i class="fas fa-hand-holding-water"></i> Other Income Report | <i class="fas fa-hand-holding-water"></i> دیگر آمدنی کی رپورٹ
    *   <i class="fas fa-chart-pie"></i> Profit & Loss Statement | <i class="fas fa-chart-pie"></i> منافع و نقصان کا گوشوارہ
    *   <i class="fas fa-print"></i> Print reports | <i class="fas fa-print"></i> رپورٹس پرنٹ کریں

*   ⚙️ **Settings** | ⚙️ **ترتیبات**:
    *   <i class="fas fa-store-alt"></i> Customize Shop Information (Name, Address, Phone, Currency) | <i class="fas fa-store-alt"></i> دکان کی معلومات کو حسب ضرورت بنائیں (نام، پتہ، فون، کرنسی)

*   💾 **Data Management** | 💾 **ڈیٹا کا انتظام**:
    *   <i class="fas fa-download"></i> Backup data to a JSON file | <i class="fas fa-download"></i> JSON فائل میں ڈیٹا کا بیک اپ لیں
    *   <i class="fas fa-upload"></i> Restore data from a JSON file | <i class="fas fa-upload"></i> JSON فائل سے ڈیٹا بحال کریں

*   🌐 **Offline First & Secure** | 🌐 **آف لائن فرسٹ اور محفوظ**:
    *   <i class="fas fa-wifi-slash"></i> Works completely offline once loaded. | <i class="fas fa-wifi-slash"></i> لوڈ ہونے کے بعد مکمل طور پر آف لائن کام کرتا ہے۔
    *   <i class="fas fa-shield-alt"></i> All data is stored locally in your browser using IndexedDB. No data leaves your device. | <i class="fas fa-shield-alt"></i> تمام ڈیٹا IndexedDB کا استعمال کرتے ہوئے آپ کے براؤزر میں مقامی طور پر محفوظ کیا جاتا ہے۔ کوئی ڈیٹا آپ کے ڈیوائس سے باہر نہیں جاتا۔

---

## 💻 Tech Stack | 💻 ٹیکنالوجی اسٹیک

*   <i class="fab fa-html5"></i> **HTML5** | <i class="fab fa-html5"></i> **ایچ ٹی ایم ایل 5**
*   <i class="fab fa-css3-alt"></i> **CSS3** (with modern UI/UX design) | <i class="fab fa-css3-alt"></i> **سی ایس ایس 3** (جدید UI/UX ڈیزائن کے ساتھ)
*   <i class="fab fa-js-square"></i> **JavaScript (ES6+)** (Vanilla JS, no frameworks) | <i class="fab fa-js-square"></i> **جاوا اسکرپٹ (ES6+)** (ونیلا جے ایس، کوئی فریم ورک نہیں)
*   <i class="fas fa-database"></i> **IndexedDB** (for local browser storage) | <i class="fas fa-database"></i> **انڈیکسڈ ڈی بی** (مقامی براؤزر اسٹوریج کے لیے)
*   <i class="fas fa-icons"></i> **Font Awesome** (for icons) | <i class="fas fa-icons"></i> **فونٹ اوسم** (آئیکنز کے لیے)

---

## 🚀 How to Use | 🚀 استعمال کا طریقہ

1.  📥 **Download/Clone:** Download the `index.html` file or clone the repository. | 📥 **ڈاؤن لوڈ/کلون کریں:** `index.html` فائل ڈاؤن لوڈ کریں یا ریپوزٹری کو کلون کریں۔
2.  📂 **Open:** Open the `index.html` file in your preferred modern web browser (e.g., Chrome, Firefox, Edge). | 📂 **کھولیں:** `index.html` فائل کو اپنے پسندیدہ جدید ویب براؤزر (مثلاً کروم، فائر فاکس، ایج) میں کھولیں۔
3.  ✨ **Start Managing:** The application is ready to use. All data will be saved in your browser's local storage. | ✨ **انتظام شروع کریں:** ایپلی کیشن استعمال کے لیے تیار ہے۔ تمام ڈیٹا آپ کے براؤزر کے مقامی اسٹوریج میں محفوظ ہو جائے گا۔

---

## 🛠️ Future Enhancements (Ideas) | 🛠️ مستقبل میں ممکنہ اضافے (خیالات)

*   <i class="fas fa-cloud-upload-alt"></i> Optional cloud sync/backup. | <i class="fas fa-cloud-upload-alt"></i> اختیاری کلاؤڈ سنک/بیک اپ۔
*   <i class="fas fa-chart-bar"></i> More advanced reporting and analytics. | <i class="fas fa-chart-bar"></i> مزید جدید رپورٹنگ اور تجزیات۔
*   <i class="fas fa-barcode"></i> Barcode scanner integration for product entry/sales. | <i class="fas fa-barcode"></i> پروڈکٹ اندراج/سیلز کے لیے بارکوڈ اسکینر انضمام۔
*   <i class="fas fa-users-cog"></i> User roles and permissions (for multi-user shops). | <i class="fas fa-users-cog"></i> صارف کے کردار اور اجازتیں (متعدد صارفین والی دکانوں کے لیے)۔
*   <i class="fas fa-mobile-alt"></i> Progressive Web App (PWA) features for better mobile experience. | <i class="fas fa-mobile-alt"></i> بہتر موبائل تجربے کے لیے پروگریسو ویب ایپ (PWA) خصوصیات۔

---

## 👨‍💻 Author | 👨‍💻 مصنف

*   **Yasin Ullah (Pakistani)** | **یاسین اللہ (پاکستانی)**
    *   <i class="fab fa-linkedin"></i> [https://www.linkedin.com/in/yasin-ullah-029229232/]

---

## 📜 License | 📜 لائسنس

This project is licensed under the MIT License. See the `LICENSE` file for details (if you add one).
|
یہ پروجیکٹ MIT لائسنس کے تحت لائسنس یافتہ ہے۔ تفصیلات کے لیے `LICENSE` فائل دیکھیں (اگر آپ ایک شامل کرتے ہیں)۔

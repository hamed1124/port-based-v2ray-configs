<div dir="rtl">

# کانفیگ‌های V2Ray بر اساس پورت

[![وضعیت آپدیت خودکار](https://github.com/hamed1124/port-based-v2ray-configs/actions/workflows/main.yml/badge.svg)](https://github.com/hamed1124/port-based-v2ray-configs/actions/workflows/main.yml)

یک مخزن خودکار که کانفیگ‌های رایگان را جمع‌آوری کرده و بر اساس شماره پورت و نوع پروتکل دسته‌بندی می‌کند.

---

### 🔧 ویژگی‌ها

**به‌روزرسانی خودکار**
<br>
مخزن به صورت خودکار هر **۴ ساعت** یک بار به‌روز شده و جدیدترین کانفیگ‌ها را دریافت می‌کند.

**پشتیبانی از پروتکل‌های مختلف**
<br>
کانفیگ‌های پروتکل‌های `Vmess`، `Vless`، `Trojan`، `ShadowSocks` و پروتکل‌های جدیدتر جمع‌آوری می‌شوند.

**دسته‌بندی هوشمند و چندگانه**
<br>
کانفیگ‌ها به سه روش دسته‌بندی می‌شوند: بر اساس **شماره پورت**، بر اساس **نوع پروتکل**، و یک دسته ویژه برای **VLESS روی پورت‌های خاص**.

**حذف موارد تکراری**
<br>
اسکریپت به طور هوشمند کانفیگ‌های تکراری را که از منابع مختلف دریافت شده‌اند، حذف می‌کند.

---

### 🚀 نحوه استفاده (لینک‌های اشتراک)

از لینک‌های اشتراک زیر در نرم‌افزار کلاینت خود (مانند v2rayNG یا Nekoray) استفاده کنید.

---

#### ⭐ لینک‌های ویژه (VLESS روی پورت‌های پرسرعت)
این لینک‌ها فقط حاوی کانفیگ‌های **VLESS** هستند که روی پورت‌های مقاوم و پرسرعت `80`, `443`, `8080` و `8088` قرار دارند. (پیشنهاد ویژه)

**نکته:** این لینک‌ها از برنچ `beta` خوانده می‌شوند و پوشه مربوط به آن‌ها در صفحه اصلی مخزن قابل مشاهده نیست.

- **VLESS روی پورت 443:**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/beta/sub/protocols/vless/443.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/beta/sub/protocols/vless/443.txt)
  ```
- **VLESS روی پورت 80:**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/beta/sub/protocols/vless/80.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/beta/sub/protocols/vless/80.txt)
  ```
- **(سایر پورت‌های ویژه در پوشه `sub/protocols/vless` در برنچ `beta` قرار دارند)**

---

#### دسته‌بندی بر اساس نوع پروتکل
برای دریافت تمام کانفیگ‌های یک پروتکل خاص، از لینک‌های زیر استفاده کنید:

- **فقط VLESS (تمام پورت‌ها):**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/protocols/vless.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/protocols/vless.txt)
  ```
- **فقط VMess (تمام پورت‌ها):**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/protocols/vmess.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/protocols/vmess.txt)
  ```

---

#### دسته‌بندی بر اساس شماره پورت

- **تمام کانفیگ‌ها (ادغام شده):**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/all.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/all.txt)
  ```

- **پورت‌های معروف (شامل تمام پروتکل‌ها):**
  ```
  # پورت 443
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/443.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/443.txt)
  ```

---

### 📚 منابع جمع‌آوری

این پروژه کانفیگ‌ها را از مخازن تجمعی زیر دریافت می‌کند. با تشکر فراوان از صاحبان این مخازن برای کار ارزشمندشان:

- **V2ray-Configs** by [barry-far](https://github.com/barry-far/V2ray-Configs)
- **V2RayAggregator** by [mahdibland](https://github.com/mahdibland/V2RayAggregator)
- **v2ray-configs** by [Epodonios](https://github.com/Epodonios/v2ray-configs)
- **telegram-configs-collector** by [soroushmirzaei](https://github.com/soroushmirzaei/telegram-configs-collector)

---

### 👤 نویسنده

توسعه داده شده توسط **حامد**

---

### 📄 سلب مسئولیت

این مخزن تنها برای اهداف آموزشی و تحقیقاتی ایجاد شده است. کانفیگ‌ها به صورت خودکار از منابع عمومی در اینترنت جمع‌آوری می‌شوند و هیچ تضمینی برای پایداری یا امنیت آن‌ها وجود ندارد. مسئولیت استفاده از این کانفیگ‌ها بر عهده کاربر است.

</div>

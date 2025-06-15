# port-based-v2ray-configs

<div dir="rtl">

# کانفیگ‌های V2Ray بر اساس پورت

[![وضعیت آپدیت خودکار](https://github.com/hamed1124/port-based-v2ray-configs/actions/workflows/main.yml/badge.svg)](https://github.com/hamed1124/port-based-v2ray-configs/actions/workflows/main.yml)

یک مخزن خودکار که کانفیگ‌های رایگان V2Ray را جمع‌آوری کرده و بر اساس شماره پورت دسته‌بندی می‌کند.

---

### 🔧 ویژگی‌ها

**به‌روزرسانی خودکار**
<br>
مخزن به صورت خودکار هر **۴ ساعت** یک بار به‌روز شده و جدیدترین کانفیگ‌ها را دریافت می‌کند.

**پشتیبانی از پروتکل‌های مختلف**
<br>
کانفیگ‌های پروتکل‌های `Vmess`، `Vless`، `Trojan` و `ShadowSocks` جمع‌آوری می‌شوند.

**دسته‌بندی هوشمند**
<br>
کانفیگ‌ها به صورت خودکار بر اساس شماره پورت در فایل‌های جداگانه دسته‌بندی می‌شوند.

**پورت‌های اولویت‌بندی شده**
<br>
پورت‌های معروف (`80`, `443`, `8080`) برای دسترسی آسان در پوشه اصلی `sub` قرار گرفته و سایر پورت‌ها در پوشه `sub/other` آرشیو می‌شوند.

**حذف موارد تکراری**
<br>
اسکریپت به طور هوشمند کانفیگ‌های تکراری را که از منابع مختلف دریافت شده‌اند، حذف می‌کند.

---

### 🚀 نحوه استفاده (لینک‌های اشتراک)

از لینک‌های اشتراک زیر در نرم‌افزار کلاینت خود (مانند v2rayNG یا Nekoray) استفاده کنید.

- **تمام کانفیگ‌ها (ادغام شده):**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/all.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/all.txt)
  ```

- **پورت‌های معروف:**
  ```
  # پورت 443
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/443.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/443.txt)

  # پورت 80
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/80.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/80.txt)
  ```

- **سایر پورت‌ها (مثال برای پورت ۲۰۵۲):**
  ```
  [https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/other/2052.txt](https://raw.githubusercontent.com/hamed1124/port-based-v2ray-configs/main/sub/other/2052.txt)
  ```

---

### ⚙️ نحوه عملکرد

این پروژه با استفاده از **GitHub Actions** یک اسکریپت پایتون را به صورت زمان‌بندی شده اجرا می‌کند. این اسکریپت وظایف زیر را انجام می‌دهد:

1.  دریافت لیست کانفیگ‌ها از چندین منبع عمومی.
2.  تحلیل هر لینک کانفیگ برای شناسایی پروتکل و پورت.
3.  دسته‌بندی کانفیگ‌ها در فایل‌های مجزا بر اساس پورت.
4.  ثبت (Commit) فایل‌های به‌روز شده در همین مخزن.

---

### 📚 منابع جمع‌آوری

این پروژه کانفیگ‌ها را از مخازن تجمعی زیر دریافت می‌کند. با تشکر فراوان از صاحبان این مخازن برای کار ارزشمندشان:

- **V2RayAggregator** by [mahdibland](https://github.com/mahdibland/V2RayAggregator)
- **V2Hub** by [yebekhe](https://github.com/yebekhe/V2Hub)
- **v2ray-configs** by [ALIILAPRO](https://github.com/ALIILAPRO/v2ray-configs)
- **telegram-configs-collector** by [soroushmirzaei](https://github.com/soroushmirzaei/telegram-configs-collector)

---

### 👤 نویسنده

توسعه داده شده توسط **حامد**

---

### 📄 سلب مسئولیت

این مخزن تنها برای اهداف آموزشی و تحقیقاتی ایجاد شده است. کانفیگ‌ها به صورت خودکار از منابع عمومی در اینترنت جمع‌آوری می‌شوند و هیچ تضمینی برای پایداری یا امنیت آن‌ها وجود ندارد. مسئولیت استفاده از این کانفیگ‌ها بر عهده کاربر است.

</div>

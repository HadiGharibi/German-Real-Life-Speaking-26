# German Real-Life Speaking — Course Progress

## Machine-Authoritative State

- current_lesson: `DE-ALLTAG-002`
- status: `completed`
- next_lesson: `DE-ALLTAG-003`

## HARD RULE — «درس امروز»

برای فرمان `درس امروز`، این فایل **تنها مرجع تعیین اینکه چه درسی باید نمایش داده یا ساخته شود** است.

### اگر status = active

- همان `current_lesson` باید از GitHub خوانده شود.
- محتوای همان فایل باید بدون بازنویسی نمایش داده شود.
- تولید مجدد، خلاصه‌سازی، بازسازی از حافظه یا ساخت نسخهٔ مشابه ممنوع است.

### اگر status = completed

- `next_lesson` باید ساخته شود.
- هیچ منطق دیگری حق ندارد شمارهٔ درس را تغییر دهد.
- تاریخ امروز، تعداد دفعاتی که امروز کاربر گفته «درس امروز»، سابقهٔ چت، حافظه، عنوان چت یا این حدس که «امروز قبلاً درس ساخته شده» نباید استفاده شود.
- در وضعیت فعلی، خروجی درست فرمان `درس امروز` فقط این است: ایجاد و انتشار `DE-ALLTAG-003` طبق `LESSON-STANDARD.md`.

## Publication Rule

برای ایجاد درس جدید:

1. `LESSON-STANDARD.md` خوانده شود.
2. `PROGRESS.md` خوانده شود.
3. درس‌های قبلی و Spaced-Repetition-Markerها از GitHub خوانده شوند.
4. فقط یک نسخهٔ نهایی ساخته شود.
5. ابتدا فایل درس در GitHub ذخیره شود.
6. `README.md` و `INDEX.md` همان موقع به‌روزرسانی شوند.
7. این فایل `PROGRESS.md` به وضعیت جدید تغییر کند:
   - `current_lesson` = درس تازه منتشرشده
   - `status` = `active`
   - `next_lesson` = شمارهٔ بعدی
8. همهٔ فایل‌ها دوباره از GitHub verify شوند.
9. فقط محتوای فایل درس verify‌شده نمایش داده شود.

## Source of Truth

- GitHub Source of Truth است.
- حافظه و سابقهٔ چت برای تعیین شماره یا متن درس مجاز نیستند.
- اگر وضعیت GitHub با حافظه/چت تناقض داشت، وضعیت GitHub برنده است.

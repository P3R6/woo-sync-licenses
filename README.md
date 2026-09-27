# woo-sync — اشتراک‌ها

`licenses.json` فهرست امضاشدهٔ اشتراک‌های woo-sync است: برای هر اشتراک فقط یک شناسه — نه خود کد اشتراک — با تاریخ پایان، و اینکه لغو شده یا نه. اسم فروشگاه‌ها و کدها اینجا نیست.

برنامهٔ هر فروشگاه هر چند ساعت این فایل را می‌خواند و امضایش را با کلید سازنده بررسی می‌کند. دستی ویرایشش نکنید: فایلی که امضایش نخواند از طرف همهٔ برنامه‌ها نادیده گرفته می‌شود. تغییرها فقط از صفحهٔ «مدیریت اشتراک‌ها» روی کامپیوتر سازنده انجام می‌شود.

---

The signed list of woo-sync subscriptions: for each, an id derived from its
code by a slow hash (not the code itself), an end date, and whether it is
cancelled. No shop names, no codes. Every copy reads it every few hours and
checks the signature. Do not edit it by hand -- changes come only from the
owner's own «مدیریت اشتراک‌ها» page.

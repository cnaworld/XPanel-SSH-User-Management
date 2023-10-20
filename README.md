

تغییر نام کاربری، کلمه عبور و پورت همچنین حذف XPanel از روی سرور (نسخه 3.6 به بالاتر)
```
bash /root/xpanel.sh OR bash xpanel.sh  OR xpanel
```
برای نصب کافیست دستور زیر را وارد کنید<br>

```
bash <(curl -Ls https://raw.githubusercontent.com/cnaworld/XPanel-SSH-User-Management/main/install.sh --ipv4)
```

حل مشکل عدم ارتباط  تماس صوتی و تصویری در اپلیکشن
```
bash <(curl -Ls https://raw.githubusercontent.com/cnaworld/XPanel-SSH-User-Management/main/fix-call.sh --ipv4)
```
دستور بالا را در ترمینال وارد کنید سپس برای UDPGW پورت جدید تعریف کنید بهتر است به جای پورت 7300 پورت 7301 یا 7302 را تنظیم کنید
<br>
<br>

## بهینه سازی سرور
نصب و حذف تنظیمات با دستور زیر 
```
bash <(curl -Ls https://raw.githubusercontent.com/cnaworld/XPanel-SSH-User-Management/main/TCP-Tweaker --ipv4)
```
## فعال سازی SSL
```
bash <(curl -Ls https://raw.githubusercontent.com/cnaworld/XPanel-SSH-User-Management/main/ssl.sh --ipv4)
```

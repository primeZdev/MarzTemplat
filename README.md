# MarzTemplat<p align="center">
  <a href="https://github.com/primeZdev/MarzTemplat" target="_blank" rel="noopener noreferrer">
    <img src="https://raw.githubusercontent.com/primeZdev/MarzTemplat/main/PreviewTemplate.png" title="Marzneshin-Sub-info"/>
  </a>
</p>
<p align="center">
  <a href="https://t.me/primez_dev">
    <img src="https://img.shields.io/badge/Telegram-Join-blue?style=flat-square&logo=telegram" alt="Telegram">
  </a>
<h1 align="center"/>این قالب برای مرزنشین طراحی شده!</h1>

## مراحل نصب
1. دانلود تمپلیت
```sh
sudo wget -N -P /var/lib/marzneshin/templates/subscription/  https://raw.githubusercontent.com/primeZdev/MarzTemplat/index.html
```

2. با دستور زیر ادرس فایل دانلود شده رو به پنل بدید
```sh
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzneshin/templates/"' | sudo tee -a /etc/opt/marzneshin/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /etc/opt/marzneshin/.env
```

3. ری استارت مرزنشین جهت ثبت تغییرات
```sh
marzneshin restart
```


## شخصی سازی ها
### اول فایل تمپلیت رو باز کنید
```
nano /var/lib/marzneshin/templates/subscription/index.html
```
1. برای ثبت برند خود در بخش خوش آمد گویی

با دکمه های Ctrl + W  در فایل باز شده عبارت پایین رو سرچ و نام برند خود را جایگزین کنید
```
خوش آمدید
```

2. برای ثبت ادرس پشتیبان تلگرام و واتسپ عبارت پایین رو سرچ و ادرس خودتون رو جایگزین کنید
```
https://t.me/YourTelegram
```
```
https://wa.me/YourWhatsApp
```
##
<br>
<br>

> **فراموش نکنید که با دادن استار (⭐) از این پروژه حمایت کنید!**  <br>


[![Stargazers over time](https://starchart.cc/primeZdev/MarzTemplat.svg?variant=adaptive)](https://starchart.cc/primeZdev/MarzTemplat)

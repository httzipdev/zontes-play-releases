# Zontes Play: releases

> [!WARNING]
> **This is a test repository. Nothing here has been verified.** No build has been tried on a real
> Zontes yet, and any release may not connect, may misbehave or may change without notice. Use it
> at your own risk, and set it up before you ride, never while riding.
>
> **Đây chỉ là repo thử nghiệm, chưa có gì được kiểm chứng.** Chưa bản build nào được chạy thử trên
> xe Zontes thật; mọi bản phát hành đều có thể không kết nối được, chạy sai hoặc thay đổi mà không
> báo trước. Tự chịu rủi ro khi dùng, và chỉ cài đặt khi xe đứng yên, không thao tác khi đang lái.

Downloads of **Zontes Play**: wireless Android Auto (Google Maps, Waze, music, the Assistant) on the
dash of your Zontes, from an Android phone, over Wi‑Fi. It works with Zontes dashes that show a
**MotoPlay / EasyConnect (Carbit) pairing QR**. Vietnamese by default, English in Settings →
Language. **Not an official Zontes app.**

## Install

1. Download `Zontes-Play-….apk` from [Releases](https://github.com/httzipdev/zontes-play-releases/releases).
   For now every build is a pre-release (`0.1.0-dev.N`).
2. If Play Protect warns, it's because the app isn't on the Play Store: **More details → Install anyway**.
3. Android Auto 17.4+: open Android Auto settings → tap **Version** about 10 times → ⋮ →
   **Start head unit server**. Repeat the ⋮ step after a phone restart or an Android Auto update.
4. Open the phone-connection screen on the dash so it shows the QR, then tap **Connect** and scan it.

A newer build installs over the previous one and keeps your settings.

## Models

Reported working with RideScreen AA, the app this one is based on: **125X / 125V**, **125M**,
**368 G / K / E**, **703F**, **703T**, **703RR**. In testing: **T350X** and **350D**. Other Zontes
TFT dashes with a pairing QR may work too.

## If something fails

In the app, **❓ Help → Share logs**, and open an [issue](https://github.com/httzipdev/zontes-play-releases/issues)
with the log, your model and year. Logs hide serial numbers and passwords.

## Credits and license

A fork of [RideScreen AA](https://github.com/mgb1982/ridescreen-aa) by Manel (mgb1982), itself
based on [OpenCfMoto](https://github.com/zanderp/open-cfmoto) by Alexandru (zanderp).
AGPL‑3.0‑or‑later, see [LICENSE](LICENSE) and [NOTICE](NOTICE). Not affiliated with Zontes, CFMoto,
Carbit or Google. Android Auto is a trademark of Google LLC.

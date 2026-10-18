# AULA F75 control

Подсветка, переназначение клавиш, макросы и профили для клавиатуры AULA F75 без фирменной программы.

Lighting, key remapping, macros and profiles for the AULA F75 keyboard, no vendor software needed.

**[Скачать / Download](https://github.com/Baklatech/aula-f75-software/releases/latest)**: Windows (installer или portable) и Linux.

На Linux дай себе доступ к клавиатуре (кабель, режим USB) / on Linux, allow access first:

```bash
sudo cp 60-aula-f75.rules /etc/udev/rules.d/ && sudo udevadm control --reload
# переподключи кабель / replug the cable
./aula-f75
```

Неофициальная, пишет в память клавиатуры, на свой страх и риск. Unofficial, use at your own risk. [Подробно / Details](docs/guide.md).

Навайбкожено в [Baklatech](https://github.com/Baklatech) · GPL-3.0

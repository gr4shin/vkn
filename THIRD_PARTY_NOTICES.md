# Сторонние компоненты

Этот документ перечисляет основные компоненты текущего окружения сборки. Оригинальные тексты скопированы без изменения из установленных пакетов. Их права и условия сохраняются независимо от условий собственного приложения VKN.

| Компонент | Версия | Лицензия пакета | Текст |
| --- | --- | --- | --- |
| AndroidX Media3 (Android: Transformer, ExoPlayer HLS и зависимые модули) | 1.11.1 | Apache-2.0 | [LICENSE](licenses/androidx-media3-LICENSE), [исходники](https://github.com/androidx/media/tree/1.11.1) |
| electron | 44.4.5 | MIT | [LICENSE](licenses/electron-LICENSE) |
| axios | 1.20.0 | MIT | [LICENSE](licenses/axios-LICENSE) |
| axios-cookiejar-support | 6.0.5 | MIT | [LICENSE](licenses/axios-cookiejar-support-LICENSE) |
| ffmpeg-static | 5.3.0 | GPL-3.0-or-later | [LICENSE](licenses/ffmpeg-static-LICENSE) |
| hls.js | 1.7.3 | Apache-2.0 | [LICENSE](licenses/hls.js-LICENSE) |
| koffi | 3.3.2 | MIT | [LICENSE.txt](licenses/koffi-LICENSE.txt) |
| lottie-web | 5.13.0 | MIT | [LICENSE.md](licenses/lottie-web-LICENSE.md) |
| qrcode | 1.5.4 | MIT | [license](licenses/qrcode-license) |
| qs | 6.16.0 | BSD-3-Clause | [LICENSE.md](licenses/qs-LICENSE.md) |
| tough-cookie | 6.0.2 | BSD-3-Clause | [LICENSE](licenses/tough-cookie-LICENSE) |

## Electron и Chromium

Electron использует Chromium, Node.js и дополнительные компоненты со своими лицензиями. Полные уведомления Chromium поставляются в `LICENSES.chromium.html` вместе с Electron в дистрибутиве; эта таблица не заменяет их и не является полным перечнем транзитивных зависимостей.

## FFmpeg

Используется готовая сборка через ffmpeg-static 5.3.0, upstream release `b6.1.1`. Лицензия пакета — GPL-3.0-or-later. В проверенной Windows-сборке FFmpeg 6.1.1 заявлена GPLv3+; исходный текст лицензии и сведения поставщика сохранены в [ffmpeg.exe.LICENSE](licenses/ffmpeg.exe.LICENSE) и [ffmpeg.exe.README](licenses/ffmpeg.exe.README).

Сведения Windows-поставщика ссылаются на [исходный коммит FFmpeg](https://github.com/FFmpeg/FFmpeg/commit/e38092ef93), перечисляют конфигурацию и версии внешних библиотек. Поставщик бинарных файлов ffmpeg-static: [релиз b6.1.1](https://github.com/eugeneware/ffmpeg-static/releases/tag/b6.1.1). Материалы должны соответствовать фактически распространяемому бинарному файлу; Windows-уведомление не подтверждает состав Linux-сборки.

Распространение GPL-компонента требует выполнения его условий, включая доступ к соответствующим исходникам и материалам сборки. Один этот документ, ссылка на upstream или отметка о закрытом коде VKN не заменяют эти требования. [Правила FFmpeg](https://ffmpeg.org/legal.html).

Собственный код VKN пока закрыт. Уведомление VKN не меняет лицензию FFmpeg и не отнимает права, которые предоставляют лицензии сторонних компонентов.

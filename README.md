# VibeScribe

Локальный голосовой ввод для Windows x64. Удерживайте горячую клавишу, говорите и отпускайте — приложение распознаёт речь на компьютере и вставляет текст в выбранное поле.

**[Скачать установщик для Windows](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Setup.exe)**

[Portable ZIP](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Portable.zip) · [Все версии и изменения](https://github.com/siniycosmonavt/VibeScribe-Releases/releases)

- Распознавание русской и английской речи работает локально, без облачного ASR.
- Интерфейс на русском и английском.
- CPU включён; модели и NVIDIA CUDA скачиваются отдельно из приложения.
- Встроенная проверка обновлений. Скачивание и перезапуск — по вашему выбору.
- История диктовок включается по желанию. Аудио и тексты не загружаются в сеть.

Лёгкий установщик — около 90 МБ. После запуска откройте настройки и скачайте модель: Turbo Q5 (RU/EN, 574 МБ), Small Q5 (RU/EN, 190 МБ) или Base English (EN, 148 МБ), затем нажмите «Использовать». Дополнительная CUDA — 675 МБ. Полный [offline-комплект](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Offline.zip) включает все модели и CUDA. Для установки и подготовки обновлений оставьте несколько гигабайт свободного места. На новом компьютере может потребоваться Microsoft Visual C++ Runtime x64; установщик предложит его установку. Для portable-версии используйте ссылку Microsoft-Visual-Cpp.url из комплекта.

При переходе с версии 0.3.0 выйдите из приложения через меню в трее и запустите установщик. Настройки и сохранённая история сохранятся. В дальнейшем используйте раздел «Обновления приложения» в настройках.

Установщик пока без цифровой подписи издателя: Windows может показывать предупреждение о неизвестном издателе. Контрольные суммы доступны в файле SHA256SUMS.txt каждого выпуска.

В этом репозитории размещаются готовые сборки и сведения о выпусках. Исходники приложения здесь не публикуются. Лицензии сторонних компонентов включены в комплект.

## English

Local voice input for Windows x64. Hold the hotkey, speak, then release to insert text. Russian and English speech recognition runs on your computer. The interface supports Russian and English.

Use the **Windows installer** link above, or download the **portable ZIP**. The CPU backend is bundled (installer about 90 MB). Download Turbo Q5 (RU/EN, 574 MB), Small Q5 (RU/EN, 190 MB), or Base English (148 MB) from Settings, then click Use. Optional CUDA is 675 MB. The Offline ZIP includes all models and CUDA. Leave several GB of disk space for installation and update preparation. Microsoft Visual C++ Runtime x64 may be required on a new PC.

VibeScribe checks for updates and lets you choose when to download and restart. Audio and transcripts are never uploaded. To upgrade from 0.3.0, quit the old app from its tray menu and run the installer; existing settings and saved history are preserved.

The installer is not yet publisher-signed; Windows may show an unknown-publisher warning. Release checksums are in SHA256SUMS.txt. This repository distributes application binaries, release notes and third-party license notices; it does not contain the application source code.

Обновления моделей проверяются отдельно и включаются по вашему выбору; прежнюю модель можно вернуть. При переходе с 0.4 может понадобиться повторная загрузка модели. Для offline-комплекта оставьте минимум 5 ГБ в папке данных.

Model updates are checked separately and activated only by your choice; the previous model remains available. Upgrading from 0.4 may require a new model download. Leave at least 5 GB free in the data location for the offline bundle.

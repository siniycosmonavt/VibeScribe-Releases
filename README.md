# VibeScribe

Локальный голосовой ввод для Windows x64. Удерживайте горячую клавишу, говорите и отпускайте — приложение распознаёт речь на компьютере и вставляет текст в выбранное поле.

**[Скачать установщик для Windows](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Setup.exe)**

[Portable ZIP](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Portable.zip) · [Все версии и изменения](https://github.com/siniycosmonavt/VibeScribe-Releases/releases)

- Распознавание русской речи работает локально, без облачного ASR.
- Интерфейс на русском и английском.
- CPU и NVIDIA CUDA; модель включена в комплект.
- Встроенная проверка обновлений. Скачивание и перезапуск — по вашему выбору.
- История диктовок включается по желанию. Аудио и тексты не загружаются в сеть.

Размер скачивания — около 1,3 ГБ из-за включённой модели и компонентов распознавания. Для установки и подготовки обновлений оставьте несколько гигабайт свободного места. На новом компьютере может потребоваться Microsoft Visual C++ Runtime x64; установщик предложит его установку. Для portable-версии используйте ссылку Microsoft-Visual-Cpp.url из комплекта.

При переходе с версии 0.3.0 выйдите из приложения через меню в трее и запустите установщик. Настройки и сохранённая история сохранятся. В дальнейшем используйте раздел «Обновления приложения» в настройках.

Установщик пока без цифровой подписи издателя: Windows может показывать предупреждение о неизвестном издателе. Контрольные суммы доступны в файле SHA256SUMS.txt каждого выпуска.

В этом репозитории размещаются готовые сборки и сведения о выпусках. Исходники приложения здесь не публикуются. Лицензии сторонних компонентов включены в комплект.

## English

Local voice input for Windows x64. Hold the hotkey, speak, then release to insert text. Russian speech recognition runs on your computer. The interface supports Russian and English.

Use the **Windows installer** link above, or download the **portable ZIP**. The model, CPU backend and NVIDIA CUDA backend are bundled (about 1.3 GB). Leave several GB of disk space for installation and update preparation. Microsoft Visual C++ Runtime x64 may be required on a new PC.

VibeScribe checks for updates and lets you choose when to download and restart. Audio and transcripts are never uploaded. To upgrade from 0.3.0, quit the old app from its tray menu and run the installer; existing settings and saved history are preserved.

The installer is not yet publisher-signed; Windows may show an unknown-publisher warning. Release checksums are in SHA256SUMS.txt. This repository distributes application binaries, release notes and third-party license notices; it does not contain the application source code.

# VibeScribe

**Голосовой ввод для Windows и ежедневная практика ясной речи.**

Надиктовывайте сообщения, заметки и рабочие тексты на русском или английском. Удерживайте горячую клавишу, говорите и отпускайте — VibeScribe распознаёт речь на вашем компьютере и вставляет текст в выбранное поле. После загрузки модели диктовка работает без интернета. Аккаунт не нужен, голос и распознанный текст не отправляются в сеть.

VibeScribe также задуман как тренажёр осознанной речи: перечитывая диктовку, вы можете замечать слова-паразиты, лишние повторы и незавершённые мысли, а затем пробовать сформулировать их яснее.

**[Скачать установщик для Windows](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Setup.exe)**

[Portable ZIP](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Portable.zip) · [Offline-комплект](https://github.com/siniycosmonavt/VibeScribe-Releases/releases/latest/download/VibeScribe-win-Offline.zip) · [Все версии и изменения](https://github.com/siniycosmonavt/VibeScribe-Releases/releases) · [English](#english)

## Почему мы не «улучшаем» речь автоматически

**Мы принципиально не вырезаем слова-паразиты и не переписываем ваши фразы после распознавания.** Автоматическое редактирование технически возможно. Отказ от него — осознанный выбор: одна из задач VibeScribe — помогать вам тренировать собственную речь.

Когда «ну», «как бы», «типа» или «короче» появляются по привычке и не добавляют смысла, их полезно увидеть в своей диктовке. Автоматическая очистка скрыла бы этот материал для самонаблюдения. Сохраняя распознанные слова, VibeScribe даёт повод заметить речевую привычку и в следующий раз выразить мысль без неё. При этом сами по себе эти слова не всегда лишние: всё зависит от контекста.

Наша цель — чтобы со временем вы говорили яснее, внимательнее относились к дикции и реже использовали слова-паразиты. Это принцип программы, который относится ко всем доступным моделям распознавания.

VibeScribe не использует языковую модель для редакторского «улучшения» текста и не применяет отдельный фильтр слов-паразитов. При этом Whisper может ошибаться, пропускать слова и самостоятельно расставляет пунктуацию. Абсолютная дословность не гарантируется. Здесь тренировка строится на вашем внимании к результату: приложение не выставляет оценок дикции и не подсчитывает слова-паразиты.

## Как использовать диктовку для тренировки

1. Надиктуйте короткую заметку или сообщение в обычном для себя темпе.
2. Перечитайте текст: где появились ненужные слова, повторы или запутанная формулировка?
3. Если заметили такую привычку, попробуйте надиктовать мысль ещё раз — с осмысленными паузами и более чёткой формулировкой.

Так повседневный голосовой ввод становится поводом практиковать ясную речь. Вы сами решаете, что оставить в тексте и что изменить перед отправкой.

## Возможности

- Распознавание русской и английской речи работает локально, без облачного ASR.
- Интерфейс на русском и английском.
- CPU включён; модели и NVIDIA CUDA скачиваются отдельно из приложения.
- Встроенная проверка обновлений. Скачивание и перезапуск — по вашему выбору.
- История диктовок включается по желанию. Аудио и тексты не загружаются в сеть.
- Настраиваемая горячая клавиша, работа в трее и плавающий индикатор.
- Режимы экономии памяти и быстрого отклика.
- Если во время распознавания вы сменили окно или поле, автоматическая вставка отменяется; результат можно скопировать из VibeScribe. Программа не нажимает Enter и не отправляет сообщение за вас.

## Начало работы

1. Установите VibeScribe или распакуйте весь Portable ZIP и запустите `VibeScribe.exe` из корня архива.
2. В настройках моделей скачайте и включите подходящую модель. Выберите русский или английский язык диктовки — он не зависит от языка интерфейса. Для совместимой видеокарты NVIDIA можно дополнительно загрузить CUDA.
3. Поставьте курсор в поле ввода. Удерживайте F8 и начинайте говорить, когда появится «Слушаю вас».
4. Отпустите F8 и дождитесь текста, сохраняя фокус в том же поле. Проверьте результат перед отправкой. Escape отменяет активную запись.

Закрытие главного окна оставляет приложение в трее. Для полного завершения выберите «Выход» в меню значка VibeScribe.

## Модели и требования

Лёгкий установщик занимает около 90 МБ и содержит движок для работы на процессоре. Модель загружается отдельно один раз:

| Модель | Языки диктовки | Размер загрузки |
| --- | --- | --- |
| Turbo Q5 | Русский, английский | 574 МБ |
| Small Q5 | Русский, английский | 190 МБ |
| Base English | Только английский | 148 МБ |

Дополнительный компонент NVIDIA CUDA — 675 МБ. Для работы на процессоре он не нужен. Загрузки компонентов поддерживают продолжение после обрыва связи; перед использованием проверяются контрольные суммы. Обновления моделей включаются по вашему выбору; прежнюю модель можно вернуть.

Offline-комплект включает все три модели и CUDA. Для него оставьте минимум 5 ГБ свободного места в папке данных: при первом запуске компоненты проверяются и копируются туда. Для установки программы и подготовки обновлений также требуется свободное место.

Windows 10/11 x64, микрофон; рекомендуется современный процессор и не менее 8 ГБ оперативной памяти. Для ускорения NVIDIA нужен совместимый драйвер и достаточно видеопамяти. На AMD/Intel используется процессор. Скорость и точность зависят от оборудования, модели и качества записи.

На новом компьютере может потребоваться Microsoft Visual C++ Runtime x64; установщик предложит его установку. Для portable-версии ссылка `Microsoft-Visual-Cpp.url` включена в комплект. Отдельная установка Python или .NET SDK не требуется.

Одна диктовка может длиться до 5 минут; во время распознавания новая запись не начинается. Защищённые поля, пароли и приложения с более высокими правами не поддерживаются. Некоторые редакторы могут не принимать автоматический ввод — в таком случае можно скопировать результат вручную.

При вставке через буфер обмена действуют настройки истории и синхронизации буфера Windows; также доступен режим ввода Unicode без буфера. Сам VibeScribe не отправляет аудио и тексты за пределы компьютера.

## Обновления и выпуски

При переходе с версии 0.3.0 выйдите из приложения через меню в трее и запустите установщик. Настройки и сохранённая история сохранятся. В дальнейшем используйте раздел «Обновления приложения» в настройках.

Автоматическую проверку обновлений можно отключить. Скачивание и перезапуск требуют вашего действия. При переходе с 0.4 может понадобиться повторная загрузка модели.

Установщик пока без цифровой подписи издателя: Windows может показывать предупреждение о неизвестном издателе. Контрольные суммы доступны в файле SHA256SUMS.txt каждого выпуска.

В этом репозитории размещаются готовые сборки и сведения о выпусках. Исходники приложения здесь не публикуются. Лицензии сторонних компонентов включены в комплект.

## English

**Local voice input for Windows, with everyday practice in clearer speech.**

Dictate messages, notes and work documents in Russian or English. Hold the hotkey, speak, then release to insert the recognized text into the selected field. Whisper runs on your computer. Once a model is downloaded, dictation works offline. No account is required. The interface supports Russian and English, independently of the dictation language.

### Why we keep filler words

**VibeScribe deliberately does not remove filler words or rewrite your sentences after recognition.** Automatic editing is technically possible. Leaving it out is a product principle: VibeScribe is also intended to help you practise clearer speech.

Reading your dictation can help you notice habitual fillers, unnecessary repetition and unfinished thoughts. Automatic cleanup would hide that material for reflection. When you spot a habit, try dictating the thought again with deliberate pauses and clearer wording. A word such as “like” is not always a filler; context matters, and you decide what belongs in your message.

This principle applies to every available recognition model. There is no LLM rewriting step or separate filler-word filter. Whisper can still make mistakes, omit words and add punctuation, so exact verbatim transcription is not guaranteed. Practice comes from reviewing your own text; the app does not score pronunciation or count filler words.

### Getting started

Use the **Windows installer** link above, or extract the entire **Portable ZIP** and launch `VibeScribe.exe` from its root. Download and activate a model in model settings, then select the dictation language. Focus a text field, hold F8 and speak when the indicator says Listening. Release F8 and keep the field focused until insertion finishes. Escape cancels recording; the hotkey is configurable.

If focus changes during recognition, automatic insertion is refused and you can copy the result from VibeScribe. The app never presses Enter or sends your message. Closing the main window keeps it in the tray; choose Exit from the tray menu to quit.

### Downloads and requirements

Windows 10/11 x64 and a microphone are required; a modern CPU and at least 8 GB RAM are recommended. The CPU engine is bundled (installer about 90 MB). Choose Turbo Q5 (RU/EN, 574 MB), Small Q5 (RU/EN, 190 MB), or Base English (EN only, 148 MB). Optional CUDA is 675 MB and needs a compatible NVIDIA driver and enough GPU memory. AMD/Intel graphics use CPU recognition. Downloads support resuming and are checked before use.

The Offline ZIP includes all three models and CUDA. Leave at least 5 GB free in the data location for component preparation, plus space for application installation and updates. Microsoft Visual C++ Runtime x64 may be required on a new PC; the installer offers it and the portable bundle includes a Microsoft download link. Python and the .NET SDK are not required.

Choose between memory saving and fast response modes. The floating indicator is customizable. Dictation history is optional and stays local. A recording can last up to 5 minutes; another cannot start during recognition. Password fields and applications with higher privileges are unsupported. Some editors may reject automatic input; use manual copying if needed. Clipboard insertion is subject to Windows clipboard history and sync settings; Unicode input without the clipboard is also available.

VibeScribe checks for updates and lets you choose when to download and restart. Automatic checks can be disabled. Audio and transcripts are never uploaded. To upgrade from 0.3.0, quit the old app from its tray menu and run the installer; existing settings and saved history are preserved. Model updates are activated only by your choice; the previous model remains available. Upgrading from 0.4 may require a new model download.

The installer is not yet publisher-signed; Windows may show an unknown-publisher warning. Release checksums are in SHA256SUMS.txt. This repository distributes application binaries, release notes and third-party license notices; it does not contain the application source code.

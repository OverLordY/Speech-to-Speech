# OverLord Speech-to-Speech v1.2

[Українська](#українська) · [English](#english) · [Deutsch](#deutsch)

[Завантаження та опис на OverLeX.eu](https://overlex.eu/uk/translators.html) · [Повідомити про помилку](https://github.com/OverLordY/Speech-to-Speech/issues/new)

## Українська

Програма для перекладу мовлення у майже реальному часі: говоріть українською або російською, а переклад англійською чи німецькою можна подати у навушники або через віртуальний мікрофон до конференції.

### Можливості

- На вибір: Azure Speech Translation, Gemini Live Translation або OpenAI Realtime Translation.
- Вибір мікрофона й пристрою виведення; маршрут через VB-Audio Virtual Cable для Zoom, Google Meet та інших застосунків.
- Локальна перевірка аудіо без API, індикація стану та можливість зупинки.
- Текст розмови й збереження повного транскрипту в TXT.
- Вибір вихідної мови: англійська або німецька; для Azure потрібно також обрати вхідну мову та регіон ресурсу.

### Перший запуск

1. Завантажте EXE з офіційної сторінки нижче та запустіть його у Windows.
2. Оберіть сервіс і введіть **власний** API-ключ; для Azure додайте регіон і вхідну мову.
3. Оберіть фізичний мікрофон і вихід. Для конференції: вихід програми — CABLE Input, мікрофон конференції — CABLE Output.
4. Перевірте аудіо, натисніть «Старт» і говоріть короткими завершеними фразами.

Версія 1.2 покращує вставлення ключів, експорт повного транскрипту та аудіодіагностику. Це сценарій передачі перекладу вашого голосу співрозмовнику, а не автоматичний двосторонній переклад його мовлення.

### Вимоги та конфіденційність

Windows x64, інтернет, відповідні аудіопристрої та власні доступи до обраних сервісів. Залежно від провайдера, користування API може бути платним; перевіряйте актуальні умови у провайдера. Інсталяція віртуального кабелю, якщо він потрібен, виконується окремо. Дані передаються стороннім сервісам для обробки.

Завантажуйте програму лише з [офіційної сторінки OverLeX](https://overlex.eu/uk/translators.html). В Issues опишіть версію Windows, кроки відтворення та очікуваний результат. **Не публікуйте API-ключі, токени, особисті дані або приватні записи розмов.**

## English

A Windows voice translation application for speaking Ukrainian or Russian and routing translated English or German speech to an audio output or a virtual microphone. Supports Azure Speech Translation, Gemini Live Translation and OpenAI Realtime Translation; includes device selection, a local API-free audio test and TXT transcript export. For meetings, route the app to CABLE Input and select CABLE Output as the conference microphone.

[Download and requirements](https://overlex.eu/en/translators.html) · [Report an issue](https://github.com/OverLordY/Speech-to-Speech/issues/new)

Requires Windows x64, internet and your own credentials for the selected services. Third-party usage may be billed. Do not post API keys or private recordings in public issues.

## Deutsch

Eine Windows-Anwendung zur Sprachübersetzung: Ukrainische oder russische Eingabe kann als englische oder deutsche Sprachausgabe an ein Audiogerät oder virtuelles Mikrofon geleitet werden. Unterstützt Azure Speech Translation, Gemini Live Translation und OpenAI Realtime Translation sowie Geräteauswahl, lokalen Audiotest ohne API und TXT-Transkriptexport.

[Download und Voraussetzungen](https://overlex.eu/de/translators.html) · [Fehler melden](https://github.com/OverLordY/Speech-to-Speech/issues/new)

Erforderlich sind Windows x64, Internet und eigene Zugangsdaten für die ausgewählten Dienste. Drittanbieter können Gebühren berechnen. Bitte keine API-Schlüssel oder privaten Aufnahmen in öffentlichen Issues veröffentlichen.

## Source code and distribution

This public repository is a project overview and support page. Source code, API keys and user recordings are **not published here**. Download the application from the official OverLeX website linked above. Availability and behavior of third-party services may change.

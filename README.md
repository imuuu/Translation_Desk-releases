# Translation Desk

A simple desktop app for reviewing and translating game text in XLIFF files, one entry at a time.
Your work stays on your own computer.

**[⬇ Download the latest version](https://github.com/imuuu/Translation_Desk-releases/releases/latest)**

[English](#english) · [Polski](#polski)

---

## English

### Install

1. **Install Python** 3.10 or newer from [python.org/downloads](https://www.python.org/downloads/), if you don't have it yet.
   The normal Windows installer is fine. Keep its default options; they include everything the app needs.
2. **Download** `Translation_Desk-<version>.zip` from the [latest release](https://github.com/imuuu/Translation_Desk-releases/releases/latest).
   Use the ZIP under *Assets*, not "Source code".
3. **Extract** the whole ZIP to a folder you can write to, for example `Documents\Translation_Desk`.
4. **Start** the app by double-clicking `Start_Windows.bat`.
   For a Polish interface, use `Start_Polski.bat` instead.

No account, subscription, API key or extra packages are needed.
On macOS or Linux, run `start.sh` (Python with Tkinter is required).

### Use

1. Click **Open file** and choose the XLIFF file (`.xlf`) you received.
2. Read the original text on the left and write the translation on the right.
3. Click **Done + Next** (or press Ctrl+Enter) to confirm an entry and move on.
4. When you are finished, click **Export XLIFF** and send the exported file back.

Your progress is saved automatically in a folder next to the XLIFF file (`<file>.xlf.translator`).
Keep that folder together with the file.

Useful extras:

- **Copy** / **Copy key** copy the original text or the entry's key.
- **Open in ChatGPT / Gemini / Claude** opens the AI website with a translation request for the current entry.
  This sends the text to that website, so use it only for text you are allowed to share.
- **Help** (F1) explains everything else.

### Updates

When a new version is available, an **⬆ Update available – Update** button appears at the top of the app.
Click it: your work is saved, the update is downloaded and checked, and the app restarts.

Updates only replace program files. Your XLIFF files, progress folders and settings are never changed.
The previous program files are kept in the `update_backups` folder.

---

## Polski

### Instalacja

1. **Zainstaluj Pythona** w wersji 3.10 lub nowszej ze strony [python.org/downloads](https://www.python.org/downloads/), jeśli jeszcze go nie masz.
   Wystarczy zwykły instalator dla Windows z domyślnymi ustawieniami, które zawierają wszystko, czego potrzebuje aplikacja.
2. **Pobierz** plik `Translation_Desk-<wersja>.zip` z [najnowszego wydania](https://github.com/imuuu/Translation_Desk-releases/releases/latest).
   Wybierz plik ZIP w sekcji *Assets*, a nie „Source code”.
3. **Rozpakuj** cały plik ZIP do folderu, w którym możesz zapisywać, na przykład `Dokumenty\Translation_Desk`.
4. **Uruchom** aplikację, klikając dwukrotnie `Start_Polski.bat` (interfejs po polsku)
   lub `Start_Windows.bat` (interfejs po angielsku).

Nie potrzebujesz konta, subskrypcji, klucza API ani dodatkowych pakietów.
Na macOS lub Linuksie uruchom `start.sh` (wymagany jest Python z Tkinter).

### Praca

1. Kliknij **Otwórz plik** i wybierz otrzymany plik XLIFF (`.xlf`).
2. Czytaj tekst oryginalny po lewej stronie i wpisuj tłumaczenie po prawej.
3. Kliknij **Gotowe + Dalej** (lub naciśnij Ctrl+Enter), aby zatwierdzić wpis i przejść dalej.
4. Na koniec kliknij **Eksportuj XLIFF** i odeślij wyeksportowany plik.

Postęp zapisuje się automatycznie w folderze obok pliku XLIFF (`<plik>.xlf.translator`).
Trzymaj ten folder razem z plikiem.

Przydatne dodatki:

- **Kopiuj** / **Kopiuj klucz** kopiują tekst oryginalny albo klucz wpisu.
- **Otwórz w ChatGPT / Gemini / Claude** otwiera stronę AI z prośbą o tłumaczenie bieżącego wpisu.
  Tekst jest wtedy wysyłany na tę stronę, więc używaj tej funkcji tylko dla tekstu, który możesz udostępniać.
- **Pomoc** (F1) wyjaśnia wszystko inne.

### Aktualizacje

Gdy dostępna jest nowa wersja, u góry aplikacji pojawia się przycisk **⬆ Dostępna aktualizacja – Aktualizuj**.
Kliknij go: Twoja praca zostanie zapisana, aktualizacja zostanie pobrana i sprawdzona, a aplikacja uruchomi się ponownie.

Aktualizacja zastępuje tylko pliki programu. Twoje pliki XLIFF, foldery postępu i ustawienia nigdy nie są zmieniane.
Poprzednie pliki programu są zachowywane w folderze `update_backups`.

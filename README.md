# Internet Radio v3 / Radio Internetowe v3

## Polski

**Internet Radio v3** to projekt odtwarzacza radia internetowego dla ESP32 z wyświetlaczem TFT ILI9488 i modułem audio DAC (PCM5102A). Projekt umożliwia odtwarzanie strumieni audio online oraz plików lokalnych z karty SD. Wersja v3 wprowadza liczne usprawnienia w wyświetlaniu informacji i obsłudze pilotem IR.

### Funkcjonalności

- Obsługa wyświetlacza TFT 480x320 z wykorzystaniem bibliotek **Adafruit GFX** i czcionek FreeSans / FreeMono w różnych rozmiarach i stylach.
- Sterowanie przy użyciu enkoderów obrotowych oraz pilota IR (NEC 38 kHz):
  - Nawigacja po stacjach radiowych i bankach
  - Regulacja głośności
  - Pauza / wznowienie odtwarzania
  - Wyciszenie dźwięku
- Obsługa do **18 banków stacji radiowych**, każdy bank zawiera do 99 stacji.
- Automatyczne pobieranie list stacji radiowych z plików JSON z GitHub.
- Obsługa odtwarzania lokalnych plików audio z karty SD.
- Wyświetlanie informacji o strumieniu audio:
  - Bitrate w b/s
  - Sample rate w Hz
  - Liczba bitów na próbkę (bits per sample)
- Wyświetlanie informacji o utworze:
  - Tytuł
  - Wykonawca
- Wyświetlanie bieżącego numeru banku i stacji.
- Automatyczny powrót do wyświetlania radia po 12 sekundach braku aktywności przy wyświetlaniu numeru banku.
- Obsługa kolorów RGB i wyraźnych kolorów dla elementów interfejsu.

### Wymagane biblioteki

- [Adafruit GFX](https://github.com/adafruit/Adafruit-GFX-Library)
- FreeFonts (FreeSans12pt7b, FreeMonoBold12pt7b, FreeMonoBold18pt7b, FreeSansBold18pt7b, FreeMono18pt7b)
- [ArduinoJson](https://github.com/bblanchon/ArduinoJson)
- [WiFiManager](https://github.com/tzapu/WiFiManager)
- [Audio](https://github.com/schreibfaul1/ESP32-audioI2S)
- SD, SPI, FS, Ticker, Time

---

## English

**Internet Radio v3** is an Internet radio player project for ESP32 with a TFT ILI9488 display and PCM5102A DAC module. The project supports online audio streams and local audio files from an SD card. Version v3 introduces improved display handling and IR remote control support.

### Features

- TFT 480x320 display support using **Adafruit GFX** library and FreeSans / FreeMono fonts in various sizes and styles.
- Control via rotary encoders and IR remote (NEC 38 kHz):
  - Navigation through radio stations and banks
  - Volume adjustment
  - Pause / resume playback
  - Mute audio
- Supports up to **18 radio banks**, each bank with up to 99 stations.
- Automatic fetching of radio station lists from JSON files on GitHub.
- Local audio file playback from SD card.
- Display of audio stream information:
  - Bitrate in b/s
  - Sample rate in Hz
  - Bits per sample
- Display of track information:
  - Title
  - Artist
- Display of current bank and station number.
- Automatic return to radio display after 12 seconds of inactivity when showing bank number.
- Use of RGB colors for clear UI elements.

### Required Libraries

- [Adafruit GFX](https://github.com/adafruit/Adafruit-GFX-Library)
- FreeFonts (FreeSans12pt7b, FreeMonoBold12pt7b, FreeMonoBold18pt7b, FreeSansBold18pt7b, FreeMono18pt7b)
- [ArduinoJson](https://github.com/bblanchon/ArduinoJson)
- [WiFiManager](https://github.com/tzapu/WiFiManager)
- [Audio](https://github.com/schreibfaul1/ESP32-audioI2S)
- SD, SPI, FS, Ticker, Time

---


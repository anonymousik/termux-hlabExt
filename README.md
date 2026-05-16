# 📱 Hacklab-Termux v3.0.0
(ARM OSINT Framework)
### Run Linux Desktop, GPU Acceleration & OSINT Tools on Android

> Zautomatyzowany framework transformujący Twoje urządzenie z systemem Android w potężną stację analityczną (OSINT) i środowisko testowe. Autoryzowany Pull Request.
> 
## 🚀 Instalacja jednym poleceniem (One-Command Deployment)
Otwórz **Termux** i wklej poniższe polecenie:
```bash
curl -sL [https://raw.githubusercontent.com/anonymousik/termux-hlabExt/main/install.sh](https://raw.githubusercontent.com/anonymousik/termux-hlabExt/main/install.sh) | bash
```
## ✨ Nowości w wersji 3.0.0 (Autor: @Anonymousik)
Wersja 3.0.0 przekształca podstawowy instalator w potężny i zautomatyzowany system operacyjny:

| Funkcja | Opis |
| :--- | :--- |
| 🤖 **Dependency Resolver** | Inteligentny system wykrywający i doinstalowujący braki w systemie przed awarią. |
| 📦 **APK Auto-Fetcher** | Zautomatyzowane pozyskiwanie wymaganych aplikacji zewnętrznych (np. klienta X11). |
| 🕵️‍♂️ **Integracja OSINT** | Dodano moduły natywne z dystrybucji Kali/Parrot (Nmap, Sherlock, Holehe, SQLMap). |
| 📡 **Remote Execute** | Moduł do bezpiecznego wczytywania i wykonywania skryptów z zewnętrznych serwerów. |
| 🌐 **Wielojęzyczne Logi (i18n)** | Przebudowany interfejs graficzny w konsoli, używający profesjonalnych strumieni INFO/WARN/ERROR. | <br> ## 🖥️ Środowisko Graficzne i Akceleracja <br> W przeciwieństwie do innych rozwiązań opartych na VNC i renderowaniu programowym (software rendering), Hacklab Nexus zapewnia **prawdziwą akcelerację sprzętową GPU**: <br> * **Zink (OpenGL na Vulkanzie)** oraz natywne sterowniki **Turnip (Adreno GPU)**. <br> * Gwarancja płynnego działania interfejsu (60 FPS) z mniejszym obciążeniem baterii. <br> ## 🛠️ Użytkowanie infrastruktury <br> Po pomyślnej instalacji wykorzystaj nowe aliasy i skrypty rozruchowe wygenerowane w folderze domowym:
| Polecenie | Akcja |
| :--- | :--- |
| ./start-nexus.sh | 🖥️ Główny plik rozruchowy środowiska XFCE4 i serwera X11. |
| ./remote-exec.sh <URL> | 📡 Automatyczne pobranie i wykonanie zdalnego payloadu. |
| cd ~/Hacklab_APKs | 📁 Dostęp do automatycznie pobranych aplikacji wymaganych do działania. |
| ./uninstall.sh | 🛑 Całkowity i bezpieczny demontaż frameworka (rollback). |

## 📋 Wymagania systemowe
 * **System:** Android 7.0+ (Zalecany Android 10+ dla pełnego wsparcia Vulkan).
 * **Termux:** Wersja z Github/F-Droid (Wersja z Google Play NIE jest obsługiwana).
 * **Miejsce na dysku:** Minimalnie 4GB wolnej przestrzeni.
## ⚠️ Zrzeczenie się odpowiedzialności (Disclaimer)
```text
To oprogramowanie służy WYŁĄCZNIE DO CELÓW EDUKACYJNYCH I BADAWCZYCH (OSINT).
Używaj infrastruktury tylko do testowania systemów, do których posiadasz pisemną zgodę.
Nieautoryzowane działania hakerskie są przestępstwem. Twórcy nie ponoszą odpowiedzialności.
```
<p align="center">
<b>🔥 Hacklab Nexus v3.0.0 - Architektura ARM zintegrowana przez @Anonymousik 🔥</b>
</p>### Run Linux Desktop, GPU Acceleration & OSINT Tools on Android
> Zautomatyzowany framework transformujący Twoje urządzenie z systemem Android w potężną stację analityczną (OSINT) i środowisko testowe. Autoryzowany Pull Request.
> 
## 🚀 Instalacja jednym poleceniem (One-Command Deployment)
Otwórz **Termux** i wklej poniższe polecenie:
```bash
curl -sL [https://raw.githubusercontent.com/anonymousik/termux-hlabExt/main/install.sh](https://raw.githubusercontent.com/anonymousik/termux-hlabExt/main/install.sh) | bash
```
## ✨ Nowości w wersji 3.0.0 (Autor: @Anonymousik)
Wersja 3.0.0 przekształca podstawowy instalator w potężny i zautomatyzowany system operacyjny:

| Funkcja | Opis |
| :--- | :--- |
| 🤖 **Dependency Resolver** | Inteligentny system wykrywający i doinstalowujący braki w systemie przed awarią. |
| 📦 **APK Auto-Fetcher** | Zautomatyzowane pozyskiwanie wymaganych aplikacji zewnętrznych (np. klienta X11). |
| 🕵️‍♂️ **Integracja OSINT** | Dodano moduły natywne z dystrybucji Kali/Parrot (Nmap, Sherlock, Holehe, SQLMap). |
| 📡 **Remote Execute** | Moduł do bezpiecznego wczytywania i wykonywania skryptów z zewnętrznych serwerów. |
| 🌐 **Wielojęzyczne Logi (i18n)** | Przebudowany interfejs graficzny w konsoli, używający profesjonalnych strumieni INFO/WARN/ERROR. | <br> ## 🖥️ Środowisko Graficzne i Akceleracja <br> W przeciwieństwie do innych rozwiązań opartych na VNC i renderowaniu programowym (software rendering), Hacklab Nexus zapewnia **prawdziwą akcelerację sprzętową GPU**: <br> * **Zink (OpenGL na Vulkanzie)** oraz natywne sterowniki **Turnip (Adreno GPU)**. <br> * Gwarancja płynnego działania interfejsu (60 FPS) z mniejszym obciążeniem baterii. <br> ## 🛠️ Użytkowanie infrastruktury <br> Po pomyślnej instalacji wykorzystaj nowe aliasy i skrypty rozruchowe wygenerowane w folderze domowym:
| Polecenie | Akcja |
| :--- | :--- |
| ./start-nexus.sh | 🖥️ Główny plik rozruchowy środowiska XFCE4 i serwera X11. |
| ./remote-exec.sh <URL> | 📡 Automatyczne pobranie i wykonanie zdalnego payloadu. |
| cd ~/Hacklab_APKs | 📁 Dostęp do automatycznie pobranych aplikacji wymaganych do działania. |
| ./uninstall.sh | 🛑 Całkowity i bezpieczny demontaż frameworka (rollback). |

## 📋 Wymagania systemowe
 * **System:** Android 7.0+ (Zalecany Android 10+ dla pełnego wsparcia Vulkan).
 * **Termux:** Wersja z Github/F-Droid (Wersja z Google Play NIE jest obsługiwana).
 * **Miejsce na dysku:** Minimalnie 4GB wolnej przestrzeni.
## ⚠️ Zrzeczenie się odpowiedzialności (Disclaimer)
```text
To oprogramowanie służy WYŁĄCZNIE DO CELÓW EDUKACYJNYCH I BADAWCZYCH (OSINT).
Używaj infrastruktury tylko do testowania systemów, do których posiadasz pisemną zgodę.
Nieautoryzowane działania hakerskie są przestępstwem. Twórcy nie ponoszą odpowiedzialności.
```
<p align="center">
<b>🔥 Hacklab Nexus v3.0.0 - Architektura ARM zintegrowana przez @Anonymousik 🔥</b>
</p>

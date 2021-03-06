<!--
*** Official Duino Coin README
*** by revox, 2019-2021
-->

<p align = "center">
  <a href="https://github.com/revoxhere/duino-coin">
    <img width="80%" src="https://github.com/revoxhere/duino-coin/blob/master/Resources/ducobanner.png?raw=true" />
  </a>
  <br />
</p>
<br />
<p align = "center">
  <a href="https://duinocoin.com">
    <img src="https://img.shields.io/badge/duinocoin.com-555555.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAAmklEQVQ4T7WUQQ6AIAwEIcaX%2BALj0fdz9gM%2BxMRESQ8ktSllrciZTneX0hg6n8h5Z5pvhD%2Bu26OO17iABaCBPwEJLKFV6ZZ1GQ2HwgqlEg51ATV7GhSyXFPjBpK6UsztdQdqjSDLNYVu4JGWaQjXLh%2BmaRn5eq8ybAGRWfx3sJFNo7lw%2FxStobkcWhlKYJf1ZS1XaggPNpIv3cls33EVXWotfwAAAABJRU5ErkJggg%3D%3D" /></a>
  <a href="https://wallet.duinocoin.com">
    <img src="https://img.shields.io/badge/Online Wallet-555555.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/gh-pages/assets/whitepaper.pdf">
    <img src="https://img.shields.io/badge/whitepaper-555555.svg?style=for-the-badge&logo=Academia" /></a>
  <a href="https://app.codacy.com/manual/revoxhere/duino-coin?utm_source=github.com&utm_medium=referral&utm_content=revoxhere/duino-coin">
  <a href="https://youtu.be/bFnCdqMke34">
    <img src="https://img.shields.io/badge/YouTube_Video-Watch-fb6404.svg?style=for-the-badge&logo=Youtube" /></a>
    <br>
  <a href="https://discord.gg/kvBkccy">
    <img src="https://img.shields.io/discord/677615191793467402.svg?color=ffa502&label=Discord&logo=Discord&style=for-the-badge" /></a>
    <img src="https://img.shields.io/codacy/grade/a995acf7cd4c4211af6da874fe549ee5?color=f68e09&style=for-the-badge" /></a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-f97606.svg?style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/releases/tag/2.3">
    <img src="https://img.shields.io/badge/release-2.3-fb6404.svg?style=for-the-badge" /></a>
</p>

<h2 align="center">Duino-Coin to moneta kt??r?? mo??na wydobywa?? u??ywaj??c komputer??w, p??ytek Raspberry Pi, Arduino, ESP i nie tylko.</h2><br />

<table align="center">
  <tr>
    <th>G????wne cechy</th>
    <th>Specyfikacja</th>
  </tr>
  <tr>
    <td>
      ???? Wspierana przez ogromn?? ilo???? platform<br>
      ???? Posiada przyjazn?? spo??eczno????<br>
      ???? ??atwa w u??yciu i wymianie<br>
      ???? Dost??pna wsz??dzie<br>
      :new: W pe??ni oryginalna<br>
      :blush: Dobra dla pocz??tkuj??cych<br>
      ???? Op??acalna<br>
      ?????? ??atwa w wydobyciu<br>
      ???? O otwartym kodzie ??r??d??owym<br>
    </td>
    <td>
      ?????? Zas??b monet: Niesko??czony (przed Grudniem 2020: 350 tys. monet)<br>
      ???? Premine: <5k blok??w (<500 monet)<br>
      ??? Czas transakcji: Natychmiastowy<br>
      ???? Cyfry po przecinku: maks. 20<br>
      ???? Symbol: DUCO (???)<br>
      ?????? Algorytmy: DUCO-S1, DUCO-S1A, XXHASH +wi??cej planowanych<br>
      ??? Dystrybucja nagr??d: wspierana przez "Kolka system" pomagaj??cy sprawiedliwie nagradza?? g??rnik??w<br>
    </td>
  </tr>
</table>

<h2 align="center">Jak zacz?????</h2><br>

| Oficjalny Portfel | Oficjalne Koparki |
:------------------:|:------------------:
[<img src="https://i.imgur.com/OEh0JxK.png">](https://duinocoin.com/getting-started#register)  |  [<img src="https://i.imgur.com/QNWkoee.png">](https://duinocoin.com/getting-started#pc)

#### Oficjalne poradniki odno??nie zak??adania konta i ustawiania koparek na przer????nych urz??dzeniach s????dost??pne na <a href="https://revoxhere.github.io/duino-coin/getting-started">naszej oficjalnej stronie</a>.

<h3 align="center">Instalowanie oprogramowania Duino-Coin</h2><br>

Najprostszym sposobem na zainstalowanie program??w do obs??ugi Duino-Coin jest pobranie [najnowszego wydania](https://github.com/revoxhere/duino-coin/releases/latest) dla twojego systemu.<br>
Po pobraniu, wypakuj archiwum i uruchom wybrany program.<br>
Nie jest wymagane instalowanie ??adnych dodatkowych bibliotek.

<hr>

Je??eli chcesz uruchomi?? programy z kodu ??r??d??owego, b??dzie wymagane zainstalowanie kilku bibliotek. W wi??kszo??ci najpopularniejszych system??w unixowych (np. Ubuntu, Debian, Raspian) wygl??da to w ten spos??b:
```BASH
sudo apt install python3 python3-pip git
git clone https://github.com/revoxhere/duino-coin
cd duino-coin
python3 -m pip install -r requirements.txt
```
Je??eli u??ywasz Windowsa, pobierz [Python 3](https://www.python.org/downloads/), potem [nasze repozytorium](https://github.com/revoxhere/duino-coin/archive/master.zip), wypakuj je i otw??rz folder w konsoli. W niej wpisz:
```BASH
py -m pip install -r requirements.txt
```
Uwaga: upewnij si??????e Python i PIP s????dodane do twojej zmiennej ??rodowiskowej PATH

Po wykonaniu jednego z powy??szych krok??w mo??esz w????czy?? wybrany program (np. `python3 PC_Miner.py` LUB `py PC_Miner.py`).

<hr>

Mo??esz r??wnie?? pobra?? oprogramowanie Duino-Coin z AUR - zainstaluj je u??ywaj??c swojego ulubionego mened??era do AUR:

```BASH
sudo pacman -S git
git clone https://aur.archlinux.org/yay-git.git
cd yay-git
makepkg -si
yay -S duino-coin
```

Pakiet Duino-Coin dla AUR jest utrzymywany przez by [PhereloHD](https://github.com/PhereloHD).

<h3 align="center">Oprogramowanie stworzone przez spo??eczno????</h3><br>

**Koparki dzia??aj??ce z Duino-Coin:**
*   [Duino-Coin_Android_Cluster Miner](https://github.com/DoctorEenot/DuinoCoin_android_cluster) by DoctorEenot
*   [ESPython DUCO Miner](https://github.com/fabiopolancoe/ESPython-DUCO-Miner) by fabiopolancoe
*   [DUCO Miner for Nintendo 3DS](https://github.com/BunkerInnovations/duco-3ds) by PhereloHD & HGEpro
*   [Dockerized DUCO Miner](https://github.com/Alicia426/Dockerized_DUCO_Miner_minimal) by Alicia426
*   [nonceMiner](https://github.com/colonelwatch/nonceMiner) by colonelwatch
*   [NodeJS-DuinoCoin-Miner](https://github.com/DarkThinking/NodeJS-DuinoCoin-Miner/) by DarkThinking
*   [d-cpuminer](https://github.com/phantom32-0/d-cpuminer) by phantom32
*   [Go Miner](https://github.com/yippiez/go-miner) by yippiez
*   [ducominer](https://github.com/its5Q/ducominer) by its5Q
*   [Unofficial miners directory](https://github.com/revoxhere/duino-coin/tree/master/Unofficial%20miners)
    *   [Julia Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Julia_Miner.jl) by revox
    *   [Ruby Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Ruby_Miner.rb) by revox
    *   [Minimal Python Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Minimal_PC_Miner.py) by revox
<!--*   [Multithreaded Python Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Multithreaded_PC_Miner.py) by Bilaboz (DEPRECATED) -->

**Inne narz??dzia:**
*   [Duco-Coin Symbol Icon ttf](https://github.com/SandUhrGucker/Duco-Coin-Symbol-Icon-ttf-.h) by SandUhrGucker
*   [DUCO Browser Extension](https://github.com/LDarki/DucoExtension) by LDarki
*   [DUCO Monitor](https://siunus.github.io/duco-monitor/) by siunus
*   [duino-tools](https://github.com/kyngs/duino-tools) by kyngs
*   [Duino Stats](https://github.com/Bilaboz/duino-stats) (Discord bot) by Bilaboz
<!--*   [Duino-Coin Auto Updater](https://github.com/Bilaboz/duino-coin-auto-updater) by Bilaboz (DEPRECATED) -->

Ta lista jest aktywnie aktualizowana. Je??eli chcesz co?? do niej doda??, wy??lij PR na GitHubie lub skontaktuj si????z jednym z deweloper??w.

<h3 align="center">U??ywanie wDUCO</h3><br>

wDUCO to DUCO "zwrapowane" na sieci innej kryptowaluty - Tron. Aktualnie nie ma dla niej wiele u??y??, opr??cz przechochywania monet w zewn??trznym portfelu wymieniania wDUCO na inny token na gie??dzie JustSwap. Zanim zaczniesz u??ywa?? wDUCO, upewnij si?? ??e masz zainstalowane modu??y `tronpy` (biblioteka tron) i `cryptography` (do szyfrowania).

### Konfiguracja Wrappera wDUCO

1. Otw??rz sw??j GUI (graficzny) or CLI (konsolowy) Portfel DUCO
2. Je??eli u??ywasz portfela GUI:
    1. Otw??rz ustawienia
    2. Kliknij na przycisk **Ustawienia Wrappera**
3. Je??eli u??ywasz portfela CLI:
    1. W????cz konfigurator wrappera wpisuj??c `wrapperconf`
4. Wpisz sw??j prywatny klucz (np. klucz z tronlink) i ustaw has??o do jego zaszyfrowania

### Wrapowanie DUCO

Po ustawieniu wrappera w jednym z dw??ch portfeli mo??esz przej???? do wrapowania DUCO, czyli zamiany na wDUCO. 

1. Otw??rz swoj portfel
2. Wpisz `wrap` aby rozpocz???? proces wrapowania (CLI) lub kliknij na przycisk **Wrapuj DUCO** (GUI)
3. Pod????aj za instrukcjami wy??wietlanymi przez portfel

### Odwrapowanie DUCO

Po ustawieniu wrappera w jednym z dw??ch portfeli mo??esz przej???? do odwrapowania wDUCO, czyli zamiany spowrotem na DUCO. 
**Uwaga: upewnij si?? ??e masz kilka TRX w swoim portfelu kt??re zostanie zu??yte na prowizje sieci!** Odwrapowanie zu??yje ok. ~5 TRX (~2z??).

1. Otw??rz sw??j portfel
2. Wpisz `unwrap` aby rozpocz???? proces odwrapowania (CLI) lub kliknij na przycisk **Odrapuj DUCO** (GUI)
3. Pod????aj za instrukcjami wy??wietlanymi przez portfel

<h2 align="center">Rozw??j Duino-Coin</h2><br>

Ka??da pomoc sprawia, ??e spo??eczno???? open-source jest wspania??ym miejscem do nauki, inspiracji i tworzenia.
Nawet najmniejszy wk??ad w pom??c rozwoju projektu Duino-Coin jest przez nas bardzo doceniany.

Jak pom??c?

*   Zforkuj projekt
*   Stw??rz branch ze swoj????zmian??
*   Zastosuj swoje poprawki
*   Upewnij si??, ??e wszystko dzia??a poprawnie
*   Otw??rz Pull Request

Kod ??r??d??owy serwera, dokumentacja dla naszego API i oficjalne biblioteki do budowania w??asnych aplikacji s?? dost??pne na branchu [useful tools](https://github.com/revoxhere/duino-coin/tree/useful-tools).

<h2 align="center">Niekt??re z oficjalnie przetestowanych urz??dze??</h2><br>

*   Arduino Pro Mini / Uno / Nano (ATmega328p @ 16 MHz 5V): ~155 H/s (15-20 DUCO/dzie??)
*   NodeMCU (ESP8266 @ 160 MHz): ~9.3 kH/s (~4.5 kH/s przy 80 MHz zegarze) (8-12 DUCO/dzie??)
*   ESP32 (przy dw??ch rdzeniach): ~13 kH/s (6 kH/s (rdze?? 1) and 7 kH/s (rdze?? 2)) (WIP)

<h2 align="center">Licencja</h2><br>

Duino-Coin jest rozpowszechniany na licencji MIT. Zobacz plik `LICENSE` po wi??ceji informacji.
Niekt??re pliki niepochodz??ce od nas mog?? mie?? inne licencje - sprawd?? ich klauzuly `LICENSE` (najcz????ciej u g??ry plik??w ??r??d??owych).

<h2 align="center">Regulamin</h2><br>
1. Duino-Coin ("DUCO") s?? zarobione przez g??rnik??w - "miner??w" podczas procesu nazywanego g??rnictwem - "mining".<br/>
2. G??rnictwo to wykorzystanie algorytmu DUCO-S1 (wyja??nionego w <a href="https://github.com/revoxhere/duino-coin/blob/gh-pages/assets/whitepaper.pdf">Duino-Coin Whitepaper</a>), w kt??rym znalezienie poprawnego wyniku do problemu matematycznego daje g??rnikowi nagrod??.<br/>
3. Mining mo??e by?? oficjalnie wykonywany przy u??yciu procesor??w, p??ytek AVR (np. Arduino), komputer??w jednop??ytkowych (np. Raspberry Pi) lub p??ytek ESP32/8266 z wykorzystaniem oficjalnych miner??w (inne oficjalnie dozwolone g??rniki s?? opisane w g??rnej cz????ci README).<br/>
4. Mining przu u??yciu GPU, FPGA i innego sprz??tu o wysokiej wydajno??ci jest dozwolone, ale przy u??yciu tylko trudno??ci `EXTREME`.<br/>
5. Ka??dy u??ytkownik korzystaj??cy z g??rnik??w na trudno??ci niezgodnej dla ich wydajno??ci (patrz <a href="https://github.com/revoxhere/duino-coin/tree/useful-tools#socket-api">lista trudno??ci</a>) b??dzie automatycznie przeniesiony (Kolka system) do odpowiedniej i / lub zablokowany.<br/>
6. Ka??dy u??ytkownik zauwa??ony przy u??yciu niew??a??ciwego sprz??tu zostanie zbanowany r??cznie lub automatycznie z sieci bez uprzedzenia.<br/>
7. Banowanie polega na zablokowaniu u??ytkownikowi dost??pu do jego monet wraz z usuni??ciem konta.<br/>
8. Do wymiany kwalifikuj?? si?? tylko monety zdobyte legalnie.<br/>
9. U??ytkownicy zauwa??eni przy u??yciu VPN (lub podobnych) w z??ych zamiarach (np. omijanie limit??w) mog?? zosta?? zbanowani bez uprzedzenia.<br/>
10. Wiele kont u??ywanych do omini??cia limit??w mog?? by?? zbanowane bez uprzedzenia.<br/>
11. Konta mog?? zosta?? tymczasowo zawieszone w celu zbadania ("dochodzenia") narusze?? ToS ("naruszenie" lub "nadu??ycie").<br/>
12. Wielokrotne konta u??ywane do unikania zakaz??w zostan?? zbanowane bez uprzedzenia.<br/>
13. ????danie wymiany dokonane na oficjalnej gie??dzie DUCO-Exchange ("oficjalna gie??da") mo??e by?? op????nione i/lub odrzucone podczas dochodzenia. <br/>
14. ????dania wymiany dokonane na oficjalnej gie??dzie mog?? zosta?? odrzucone z powodu naruszenia ToS i/lub niskich funduszy.<br/>
15. DUCO u??ytkownika mog?? zosta?? usuni??te, je??li naruszenie zostanie udowodnione.<br/>
16. Niniejszy regulamin mo??e ulec zmianie w dowolnym momencie bez wcze??niejszego powiadomienia.<br/>
17. Ka??dy u??ytkownik korzystaj??cy z Duino-Coin zobowi??zuje si?? do przestrzegania powy??szych zasad.<br/>

<h4 align="center">Polityka prywatno??ci</h2><br>
1. Na serwerze g????wnym przechowujemy tylko nazwy u??ytkownik??w, zaszyfrowane has??a (za pomoc?? bcrypt) i e-maile u??ytkownik??w jako ich dane konta.<br/>
2. E-maile nie s?? publicznie dost??pne i s?? wykorzystywane wy????cznie do kontaktowania si?? z u??ytkownikiem w razie potrzeby, potwierdzania wymian na <a href="https://revoxhere.github.io/duco-exchange/">DUCO-Exchange</a> i otrzymywania okazjonalnego newslettera (planowanego na przysz??o????).<br/>
3. Salda, transakcje i dane zwi??zane z wydobyciem jest publicznie dost??pne w publicznych <a href="https://github.com/revoxhere/duino-coin/tree/useful-tools#http-json-api">JSON API</a>.<br/>
4. Polityka prywatno??ci mo??e ulec zmianie w przysz??o??ci z uprzednim powiadomieniem.

<h2 align="center">Deweloperzy</h2><br>

*   **Deweloperzy:**
    *   [@revox](https://github.com/revoxhere/) (Za??o??yciel/g????wny deweloper) - robik123.345@gmail.com
    *   [@Bilaboz](https://github.com/bilaboz/) (g????wny deweloper)
    *   [@connorhess](https://github.com/connorhess) (g????wny deweloper
    *   [@JoyBed](https://github.com/JoyBed) (g????wny deweloper)
    *   [@HGEcode](https://github.com/HGEcode) (deweloper)
    *   [@LDarki](https://github.com/LDarki) (web deweloper)
    *   [@travelmode](https://github.com/colonelwatch) (deweloper)
    *   [@ygboucherk](https://github.com/ygboucherk) (deweloper [wDUCO](https://github.com/ygboucherk/wrapped-duino-coin-v2))
    *   [@Tech1k](https://github.com/Tech1k/) - kristian@beyondcoin.io (Webmaster)
    *   [@EinWildesPanda](https://github.com/EinWildesPanda) (deweloper)

*   **Wsp????autorzy:**
    *   [@5Q](https://github.com/its5Q)
    *   [@kyngs](https://github.com/kyngs)
    *   [@httsmvkcom](https://github.com/httsmvkcom)
    *   [@Nosh-Ware](https://github.com/Nosh-Ware)
    *   [@BastelPichi](https://github.com/BastelPichi)
    *   [@suifengtec](https://github.com/suifengtec)
    *   Podzi??kowania dla [@Furim](https://github.com/Furim) za pomoc podczas wczesnego rozwoju
    *   Podzi??kowania dla [@ATAR4XY](https://www.youtube.com/channel/UC-gf5ejhDuAc_LMxvugPXbg) za pomoc w tworzeniu logotyp??w
    *   Podzi??kowania dla [@Tech1k](https://github.com/Tech1k) za wsp????prac?? z [Beyondcoin](https://beyondcoin.io) i domen?? [duinocoin.com](https://duinocoin.com)
    *   Podzi??kowania dla [@MrKris7100](https://github.com/MrKris7100) za pomoc w implementacji algorytmu SHA1
    *   Podzi??kowania dla [@daknuett](https://github.com/daknuett) za pomoc w implementacji algorytmu SHA1 dla Arduino

<hr>

Link do projektu: [https://github.com/revoxhere/duino-coin/](https://github.com/revoxhere/duino-coin/)

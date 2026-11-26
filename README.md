<p align="center"><img src="seyir.svg" width="96" alt="Seyir" /></p>

<h1 align="center">Seyir</h1>
<p align="center"><b>Yapay zekâ ne yapıyor, canlı izle.</b><br/>Rust ile yazılmış, Warp tarzı terminal · macOS, Windows ve Linux · <a href="https://k-syntax.com/tr/">K-Syntax</a></p>

<p align="center">
  <a href="https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir.dmg"><b>macOS (Apple Silicon ve Intel) · Seyir.dmg</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir-Setup.exe"><b>Windows 10/11 · Seyir-Setup.exe</b></a> &nbsp;·&nbsp;
  <a href="https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir.AppImage"><b>Linux · AppImage</b></a> (<a href="https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir.deb">.deb</a>)<br/>
  <a href="https://clay-tech.github.io/seyir/">Tanıtım sayfası</a> ·
  <a href="https://github.com/Clay-Tech/seyir/releases">Tüm sürümler</a> ·
  <a href="https://github.com/Clay-Tech/seyir/issues">Öneri / hata bildir</a>
</p>

---

- **Seyir defteri:** Giriş kutusuna `#` ile yaz; yapay zekâ kod ajanının okuduğu dosyalar, aramalar, komutlar, diff'ler ve alt ajanlar canlı kutular olarak akar. Denemek için: `# demo`
- **İzin kartı ve geri al:** ajan komut çalıştırmadan ya da dosyaya yazmadan önce sorar; onayladığın düzenlemeyi tek tıkla geri alırsın. Çalışırken araya girebilir, modeli sohbet ortasında değiştirebilirsin.
- **Çentikte ada (macOS):** Seyir arkadayken ajanın o anki adımı, izin isteği ve bitiş özeti ekranın tepesinde görünür; yalnız bir şey olduğunda gelir. İzin adanın içinden verilir; istersen Claude kotası adada sabit durur.
- **Maliyet ve kota:** bağlam doluluğu, sohbetin maliyeti, 5 saatlik ve haftalık kota canlı sayaçta; günlük kullanım ayrı pencerede.
- **Warp tarzı giriş kutusu**, **komut blokları** (zsh, bash, fish; tmux ve ssh içinde de), sekmeler, bölmeler, komut paleti (⌘P), açılışta oturumu geri yükleme.
- Ayarlar penceresi (⌘,): yazı tipi, tema, dil, bütün kısayollar. Uygulama içinden imzalı güncelleme.
- Rust + GPU çizim, Electron yok; her şey makinende kalır.

### Kurulum

**macOS:** [Seyir.dmg](https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir.dmg)'yi indir, Seyir'i Uygulamalar'a sürükle. Apple imzalı ve onaylıdır, çift tıklayınca açılır. Homebrew ile: `brew install --cask clay-tech/seyir/seyir`

**Windows:** [Seyir-Setup.exe](https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir-Setup.exe)'yi çalıştır (yönetici izni gerekmez). SmartScreen uyarırsa "Ek bilgi" › "Yine de çalıştır". Windows'ta kısayollar ⌘ yerine **Ctrl+Shift** ile çalışır (Ctrl+Shift+T, Ctrl+Shift+P…); kabuk PowerShell'dir.

**Linux:** [Seyir.AppImage](https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir.AppImage)'i indir, `chmod +x Seyir.AppImage` ile çalıştırılabilir yap ve aç; Debian/Ubuntu'da [Seyir.deb](https://github.com/Clay-Tech/seyir/releases/latest/download/Seyir.deb) de kurulabilir.

Yeni sürümler uygulamanın içinden iner ve pencereyi kapatınca kurulur.

Seyir defteri, bilgisayarında kurulu yapay zekâ kod ajanının komut satırı aracını kullanır (şu an desteklenen: Claude Code).

<sub>Bu depo yalnız sürümleri ve tanıtım sayfasını barındırır.</sub>

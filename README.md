# VYKO – Media Downloader & Converter

**by Tan Systems** · **Son sürüm: 5.4** (Android 5.4 / Web 5.4)

YouTube, Instagram, TikTok, Facebook, X ve yüzlerce siteden video/ses indirir; MP3 / MP4 / WAV / M4A'ya çevirir; keser, düzenler, birleştirir, seslendirir.

## İndir

**→ [Son sürüm (Releases)](https://github.com/4Khomedeco/VYKO/releases/latest)**

| Platform | Dosya | Not |
|---|---|---|
| **Android** | `VYKO-x.y.apk` (doğrudan kurulum) ya da `VYKO-x.y.zip` (içinde aynı APK) | Android 8.0+ (arm64). |
| **Windows (web)** | `VYKO-Web-Dagitim.zip` | Python 3.12+ gerekir; `Kur.bat`, sonra `VYKO-Web-Baslat.bat`. |

## Android kurulum (adım adım)

1. Telefonda Releases sayfasını açın, **VYKO-x.y.apk** dosyasına dokunun. Chrome "Bu tür dosya telefonunuza zarar verebilir" diyebilir → **Yine de indir**. (Bu uyarı mağaza dışından indirilen *her* APK için çıkar.)
2. İndirilenler'den APK'ya dokunun. İlk kez kuruyorsanız Android "Bu kaynaktan uygulama yüklemeye izin ver" ister → **İzin ver**, geri dönüp tekrar dokunun.
3. Play Protect "Bu uygulama tanınmıyor" diyebilir → **Yine de yükle**. Uygulama Google Play'de olmadığı için bu normaldir; "zararlı" uyarısı değildir.
4. Yükle → Aç.

**5.0 veya daha eski bir VYKO yüklüyse önce onu silin** (5.1 ile imza değişti). 5.1 ve sonrası birbirinin üstüne kurulur; yeni sürüm çıkınca uygulama ana sayfada bildirir.

**Neden uyarı çıkıyor?** Android, Play Store dışından kurulan her uygulamada bu soruları sorar; imza ya da uygulamayla ilgili değildir. Uyarıyı tamamen kaldırmanın tek yolu Play Store'dur; Play politikası YouTube'dan indiren uygulamalara izin vermediği için VYKO oradan dağıtılamaz.

**Doğrulama:** APK'nın imza sertifikası *CN=Tan Systems, OU=VYKO* ve SHA-256 parmak izi:
`8dfbfcb3db298634f5ca3128cb32af2fa57cd78f01868d5ab633f304a4039dce`
(Her sürümde aynıdır; farklıysa dosya orijinal değildir.)

## Özellikler

- Linkten indirme: site otomatik tanınır, kalite seçimi (4K'ya kadar video, 320 kbps MP3), oynatma listeleri, altyazı (SRT), kapak resmi gömme
- **Sosyal medya ön ayarları:** Reels/TikTok 9:16, YouTube 16:9, Kare 1:1, WhatsApp 16 MB
- **Toplu işlem:** seçili videoları tek seferde MP3 yap, ses dosyalarını birleştir, toplu sil
- **Bölümlere ayır:** bölümleri olan videolar ayrı MP3'ler olarak iner (bölüm adı, parça no, albüm, sanatçı etiketleriyle)
- Yeniden dene / kaldığı yerden devam; uygulama kapansa bile yarım kalan kuyruk sorulur
- Dönüştür: MP3 / MP4 / WAV / M4A, çözünürlük düşürme, telefondaki dosyalar
- Kes & Düzenle: dalga/film şeridi editörü, fade, normalize, sessizlik kırpma, hız, ters, sessiz, GIF; birleştirme; zil sesi
- Seslendirme: Microsoft nöral sesler (ücretsiz, 8 dil) ve isteğe bağlı kendi ElevenLabs anahtarınızla ElevenLabs sesleri; her sesin tanıtımı kredisiz dinlenir; Dinle (kaydetmez) / Kaydet
- Ayarlar: kayıt klasörü, tema, dil (TR/EN/DE), **yt-dlp motorunu uygulama içinden güncelleme**, **cookies.txt** ile yaş sınırlı/özel içerik, hata kaydı paylaşma, yeni sürüm bildirimi

## Sürüm bilgisi

`surum.json` uygulamanın "yeni sürüm var mı" kontrolünde kullandığı dosyadır.

## Yasal

Yalnız kendi içeriğinizi ya da indirme izniniz olan içerikleri indirin. Platformların kullanım koşullarına uymak kullanıcının sorumluluğundadır.
Bileşenler: yt-dlp (Unlicense), FFmpeg (LGPL, ffmpeg-kit), Microsoft Edge Read Aloud sesleri, ElevenLabs API (kendi hesabınız).

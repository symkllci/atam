# 10 Kasım · Sonsuza Dek

Ulu Önder Mustafa Kemal Atatürk'ü saygı ve özlemle anmak için hazırladığım, parçacık animasyonlu dikey (9:16) bir kısa video.

Kütüphane kullanılmadı; yalnızca **HTML + CSS + JavaScript (Canvas)**.

🔗 **Canlı izle:** https://symkllci.github.io/atam/

## Akış

1. **10 KASIM 1938 · 09:05**
2. İki Atatürk portresi, binlerce parçacıktan oluşan gümüş tonlu halftone görünümde
3. Dalgalanan Türk bayrağı — *Saygı ve özlemle anıyoruz*
4. **SONSUZA DEK**
5. Bayrak, **İLELEBET PAYİDAR**, Atatürk'ün sözü ve imzası

## Nasıl çalışır?

- Yazılar, bayrak ve portreler önce görünmez bir tuvale çizilir, ardından pikselleri okunarak her parçacığa bir hedef nokta verilir.
- Parçacıklar sahne değiştikçe yeni hedeflerine doğru akar.
- Portrelerde parlak bölgeler büyük, koyu bölgeler küçük noktalarla gösterilir (halftone).
- Bayrak, Türk Bayrağı Kanunu'ndaki ölçülere göre çizilir.

## Dosyalar

| Dosya | Açıklama |
|---|---|
| `index.html` | Animasyonun tüm kodu |
| `atam1.jpg`, `atam2.jpg` | Portreler |
| `imza.png` | Atatürk'ün imzası |

## Çalıştırma

Görseller tuvalde işlendiği için dosyayı çift tıklayarak değil, bir sunucu üzerinden açmak gerekir:

- VS Code'da **Live Server** eklentisiyle: `index.html` → sağ tık → *Open with Live Server*
- ya da terminalde: `npx serve .`

Tam ekran için ⛶ butonu, butonu gizlemek için `H`, baştan başlatmak için `R`.

---

*Benim naçiz vücudum elbet bir gün toprak olacaktır, fakat Türkiye Cumhuriyeti ilelebet payidar kalacaktır.*

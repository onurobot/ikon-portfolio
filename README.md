# İkon Design Architecture — Portfolio

Fuar standı ve Türkiye ulusal pavilyon tasarım & uygulama portfolyosu (2025).
Exhibition stand & national pavilion design-and-build portfolio (2025).

Tek dosyalık statik site — kurulum/derleme gerektirmez.
Single-file static site — no build step required.

## Özellikler / Features
- İki dil / Bilingual: Türkçe + English (tercih hatırlanır)
- Açık & koyu tema / Light & dark theme (varsayılan: açık)
- 12 bireysel stand + 22 ulusal pavilyon, tıkla-büyüt galeri (lightbox)
- Tamamen responsive

## Çalıştırma / Run
Herhangi bir statik sunucu yeterli:

```bash
npx serve .
```

Ardından tarayıcıda `index.html` açılır.

## Yapı / Structure
```
index.html          # tüm site (HTML + CSS + JS)
assets/
  iconlogo.png      # logo
  bireysel/*.jpg    # bireysel stand görselleri
  pavilion/*.jpg    # ulusal pavilyon görselleri
```

---
© 2025 İkon Design Architecture · info@ikontasarim.com · www.ikontasarim.com

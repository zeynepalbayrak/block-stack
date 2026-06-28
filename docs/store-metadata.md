# Block Stack — App Store metadata draft

Bu dosya **App Store Connect** form alanlarına yapıştırılmak için hazır metinleri içerir. Sağ tarafta Apple'ın karakter limitleri yazılı.

---

## 📋 App Information

| Alan | Değer |
|---|---|
| **Name** (30 char) | `Block Stack` |
| **Subtitle** (30 char) | `Bloğu zamanında bırak` |
| **Primary Category** | Games |
| **Secondary Category** | Games > Casual |
| **Bundle ID** | `com.zeynepalbayrak.blockstack` |
| **SKU** | `BLOCKSTACK001` |
| **Content Rights** | "Does not use third-party content" |
| **Age Rating** | 4+ |

---

## 🎮 App Store Listing (Türkçe)

### Promotional Text (170 char, güncellenebilir, review gerektirmez)
```
3 üst üste perfect drop yap, bloklar büyür! Continue özelliğiyle ölümden geri dön. Günlük streak ile her gün biraz daha yükseğe.
```

### Description (4000 char)
```
Block Stack — bloğu tam zamanında bırak, kuleyi yükselt.

Basit ama bağımlılık yapan minimalist yığma oyunu. Her blok bir öncekinin üzerine düşmeli. Kaçırırsan, fazlalık keser düşer. Tam hizalarsan combo başlar.

✦ ÖZELLİKLER
• Tek dokunuş — herkes ilk denemede anlar
• 3 üst üste "PERFECT" → bloklar büyür (3 IN A ROW! efekti)
• Combo sayacı, streak takip, achievement burst'leri
• 12 renkli palette — yeni paletler skor milestone'larında açılır
• Continue with Ad — öldüğünde kısa reklam izle, kaldığın yerden devam et
• Açık ve koyu mod desteği
• Sessiz mod + haptic feedback
• Günlük streak takibi — her gün oyna, sayaç artsın

✦ NASIL OYNANIR
1. Hareket eden bloğa tıkla
2. Önceki bloğun üzerine indir
3. Mükemmel hizalarsan combo artar
4. 3 perfect üst üste = bloklar büyür, daha kolay devam
5. Kaçırırsan fazlalık keser — blok küçülür
6. Blok çok küçülünce oyun biter

✦ MİNİMAL TASARIM
Reklamlar dışında hiç dikkat dağıtıcı yok. Hiç paywall yok. Hiç zorunlu kayıt yok. Açıp oyna.

Skorunu paylaş, arkadaşlarını yen.
```

### Keywords (100 char, virgülle ayır, **boşluk kullanma**)
```
stack,block,tower,kule,perfect,timing,casual,puzzle,minimal,reflex,arcade,zen,relax,strategy
```

### Support URL
```
https://zeynepalbayrak.github.io/block-stack/
```

### Marketing URL (opsiyonel)
```
https://zeynepalbayrak.github.io/block-stack/
```

### Privacy Policy URL (zorunlu)
```
https://zeynepalbayrak.github.io/block-stack/privacy.html
```

---

## 🌐 English Listing (eklemek istersen)

### Promotional Text
```
Stack 3 perfect drops in a row and blocks grow! Continue from death with a quick ad. Build daily streaks and climb higher every day.
```

### Description
```
Block Stack — drop the block at the perfect moment and grow your tower.

A simple but addictive minimalist stacking game. Each block must land on the one below. Miss, and the overhang falls off. Land perfectly, and the combo begins.

✦ FEATURES
• One tap — anyone gets it on first try
• 3 perfect drops in a row → blocks grow bigger (3 IN A ROW! effect)
• Combo counter, daily streak, achievement bursts
• 12 color palettes — new ones unlock at score milestones
• Continue with Ad — watch a short ad after dying and resume your run
• Light + dark mode
• Mute toggle + haptic feedback
• Daily streak tracking — play every day to keep your count

✦ HOW TO PLAY
1. Tap the moving block
2. Drop it onto the previous one
3. Perfect alignment builds your combo
4. 3 perfects in a row = blocks grow, easier to continue
5. A miss trims the overhang — block gets smaller
6. Too small? Game over

✦ MINIMAL DESIGN
No distractions beyond ads. No paywall. No mandatory signup. Just open and play.

Beat your best. Challenge your friends.
```

### Keywords
```
stack,block,tower,perfect,timing,casual,puzzle,minimal,reflex,arcade,zen,relax,strategy,game
```

---

## 📸 Screenshots (zorunlu)

Apple'ın istediği minimum: **iPhone 6.7"** (iPhone 15/16 Pro Max — 1320×2868 px) için en az 3 screenshot.

Önerilen 5 görsel:
1. **Açılış ekranı** — BLOCK STACK başlığı + intro stack
2. **Mid-game** — 5+ blok yığılmış, combo görünür
3. **3 IN A ROW!** burst anı
4. **Achievement** — "💯 CENTURION" rozeti
5. **Game over** — skor + stats + continue button

Simulator'dan capture: Cmd+S, dosya Desktop'a kaydolur.

---

## 🔒 Privacy "Nutrition Label" (App Store Connect)

Apple'ın sorduğu sorular ve cevaplarımız:

| Soru | Cevap |
|---|---|
| Do you collect any data? | **Yes** (üçüncü taraf — AdMob) |
| Data used to track user? | **Yes** (Advertising Data via AdMob) |
| Identifiers — Device ID | ✅ Linked to user identity, used for Advertising |
| Diagnostics — Crash data | ❌ (Capacitor varsayılan minimal) |
| Other Data — Ad interactions | ✅ Linked, for Advertising |

Hepsi AdMob aracılığıyla, biz doğrudan toplamıyoruz.

---

## 📞 App Review Information

| Alan | Değer |
|---|---|
| **First name** | Zeynep |
| **Last name** | Albayrak |
| **Email** | zeyneplbyrk@gmail.com |
| **Phone** | (kendi numaran) |
| **Demo Account** | Gerek yok (login yok) |
| **Notes** | "Block Stack is a minimalist stacking game. Ads are served via Google AdMob. App requests ATT permission on first launch (optional, decline still works)." |

---

## ✅ Release Checklist (App Store Connect'e girmeden önce)

- [ ] Apple Developer Program aktif
- [ ] App icon Xcode'da yüklü (✅ yapıldı)
- [ ] Bundle ID `com.zeynepalbayrak.blockstack` (✅)
- [ ] Privacy URL erişilebilir (https://zeynepalbayrak.github.io/block-stack/privacy.html)
- [ ] AdMob rewarded production ID yapıştırıldı (⏳)
- [ ] Version 1.0, Build 1
- [ ] Distribution build (Archive) Xcode'dan upload edildi
- [ ] Screenshots hazır
- [ ] Description + keywords yapıştırıldı
- [ ] Privacy nutrition label dolduruldu
- [ ] "Submit for Review" basıldı

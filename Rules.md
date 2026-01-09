# abc987

abc987, 4×4 harf tahtasında kelime bulmaya dayalı, oda kodu ile arkadaşlarınla aynı tahtayı paylaşabildiğin basit bir kelime oyunudur.  
Oyun iki dilde oynanabilir: **Türkçe (TR)** ve **İngilizce (EN)**.

---

## Oyun Akışı (TR)

1) **Dil seç:** TR veya EN.  
2) **Oyuncu adını gir:** 3–12 karakter. Uygunsuz isimler filtrelenir.  
3) **Oda kur veya katıl:**
   - **Yeni Oda:** 6 karakterlik oda kodu üretir.
   - **Katıl:** 6 karakterlik oda kodu ile odaya gir.
4) **Tahtada kelime bul:**
   - Tahta **4×4**’tür.
   - Aynı oda kodunda herkes **aynı tahtayı** görür.
   - Harflere tıklayarak kelime oluşturursun.
   - Seçtiğin yeni harf, bir önceki harfin **komşusu** olmalı (yatay / dikey / çapraz).  
     (Arada atlama yok.)
   - Son seçtiğin harfe tekrar tıklarsan seçimden çıkar (geri al).
5) **Kelimeyi listeye ekle:**
   - Kelime **en az 3 harf** olmalı.
   - Aynı kelimeyi aynı oyunda **iki kez ekleyemezsin**.
   - Oyun başına maksimum **400 kelime** eklenebilir.
6) **Oyunu bitir:**
   - “Oyunu Tamamla / Finish Game” ile sonuçlar gönderilir.
   - Kelimeler sözlük listesine göre doğrulanır.
   - Sonuç ekranında odanın skor tablosu görünür.

---

## Geçerli Kelime Kuralları (TR)

- **En az 3 harf** olmalı.
- Tahtadaki harfler **komşuluk kuralına** uygun seçilmeli.
- Doğrulama oyun bitince yapılır:
  - Sözlükte varsa: **geçerli** → puan alır
  - Sözlükte yoksa: **geçersiz** → puan **0**

---

## Puanlama (TR)

- **3–4 harf:** 1 puan  
- **5 harf:** 2 puan  
- **6 harf:** 3 puan  
- **7 harf:** 7 puan  
- **8+ harf:** 11 puan  

Toplam skor = yalnızca **geçerli** kelimelerin puan toplamı.

---

## Sonuç Tablosu (TR)

- Skorlar aynı oda koduna göre listelenir ve skora göre sıralanır (yüksekten düşüğe).
- Ekranda:
  - İlk **41** sonuç gösterilir.
  - Eğer sen 41’in dışında kaldıysan, **senin sonucun ayrıca en altta** gösterilir.
- Satıra tıklayarak kelime listesini açıp kapatabilirsin (detaylar sonradan yüklenebilir).

---

## Veri Saklama (TR)

- Sonuçlar yaklaşık **7 gün** saklanır.
- Süre dolunca otomatik silinmesi hedeflenir.

---

## Destek (TR)

- Oyun **ücretsizdir**.
- Destek / bahşiş tamamen **isteğe bağlıdır**.
- Destek, oyunda **avantaj / özellik / ayrıcalık sağlamaz**.

---

# abc987 (EN)

abc987 is a simple 4×4 word game where friends can play on the same board using a room code.  
It supports **Turkish (TR)** and **English (EN)**.

## How to Play (EN)

1) Choose language: TR or EN  
2) Enter player name (3–12 chars; inappropriate names are filtered)  
3) Create or join a room (6-character room code)  
4) Build words on a 4×4 board:
   - Everyone in the same room sees the **same board**
   - Each new letter must be a **neighbor** (horizontal/vertical/diagonal)
   - Click the last selected cell again to undo
5) Add word:
   - Minimum **3 letters**
   - No duplicates in the same game
   - Max **400 words** per game
6) Finish game:
   - Words are validated against the dictionary
   - Room leaderboard is shown

## Scoring (EN)

- 3–4 letters: 1  
- 5 letters: 2  
- 6 letters: 3  
- 7 letters: 7  
- 8+ letters: 11  

## Leaderboard (EN)

- Sorted by score (desc)
- Shows top **41**
- If you’re outside top 41, your result is appended at the bottom

## Data Retention (EN)

- Results are kept for about **7 days**.

## Support (EN)

- The game is free
- Tips are optional and give **no in-game advantage**

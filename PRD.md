# Okçuluk Oyunu - Yer Şekilleri Eğitim Oyunu

## Oyun Konsepti
Oyuncu yay ve ok kullanarak ekranda beliren coğrafi yer şekillerinden "akarsu yer şekilleri" olanları vuracak. Yanlış hedeflere isabette can kaybeder. Tek HTML dosyası olarak geliştirilecek.

## Ana Mekanikler

### Kontroller
- Mouse/touch ile yay hedefi belirle
- Basılı tutarak güç topla (0-100%)
- Bırakınca ok fırlar
- Ok gerçekçi fizik ile uçar: yerçekimi, rüzgar, hava direnci

### Hedefler ve Puanlama
**Her turda 2 hedef:**
- 1 doğru: Akarsu yer şekilleri (Delta Ovası, Menderes, Dev Kazanı, Birikinti Konisi, Vadi, Irmak Adası, Taraça)
- 1 yanlış: Diğer yer şekilleri (Falez, Barkan, Mantar Kaya, Hörgüç Kaya, Moren, Tombolo, Sirk Gölü, Lapya)

**Sonuçlar:**
- Doğru isabet: +5 puan, hedef parçalanır
- Yanlış isabet: -5 puan, -1 can
- Iskalama: Aynı hedefler kalır, tekrar atış hakkı

### Oyun Akışı
1. Başlangıç: 3 can, 0 puan
2. İki hedef belirir (sol ve sağ tarafta)
3. Oyuncu atar
4. Doğru/yanlış değerlendirme
5. Yeni tur veya Game Over (0 can)
6. Yeniden başlama seçeneği

## Ekran Düzeni

**Üst Kısım:**
- Sol köşe: Kalp ikonları (can sayısı)
- Sağ köşe: Rüzgar göstergesi (yön ve hız)
- Orta: Puan

**Orta Kısım:**
- 2 hedef (daire şeklinde, içinde yazı)
- Uçan oklar

**Alt Kısım:**
- Yay ve ok
- Güç barı (basınca görünür)

## Görsel Efektler
- Yay mouse/touch'ı takip eder
- Güç toplarken yay geriye çekilir, kiriş gerilir
- Ok fiziğe uygun şekilde uçar
- İsabette ekran titrer, flash efekt, parçacık patlaması
- Doğru hedefe isabet: Hedef parçalanır
- Yanlış hedefe isabet: Hedef sallanır
- Ok hedefe saplandıktan sonra kaybolur

## Rüzgar Sistemi
- Rastgele yön ve güç (3-8 m/s)
- Sürekli değişir (maksimum 10 m/s)
- Oku yolundan saptırır

## Önemli Noktalar
- Hedefler ekranın üst kısmında, birbirinden uzak
- Ok uçarken yeni atış yapılamaz
- Iskalama cezasız (öğrenme için)
- 3 hata hakkı sonra oyun biter
- Mesajlar: "Doğru!" (yeşil), "Yanlış!" (kırmızı), "Iskaladın!" (sarı)

## Hedef Kitle
Ortaokul/lise öğrencileri için coğrafya eğitimi destekleyici, eğlenceli öğrenme aracı.

# MyShop - 6 Ürünlü CSS3 Modern Web Bileşeni Projesi

## 🎯 Proje Özellikleri

- **6 Farklı Ürün Kartı**: Her biri farklı overlay etiketleriyle
- **Modern Grid Sistemi**: Flexbox ile 3-2-1 kolon responsive düzen
- **Zengin Hover Efektleri**: Büyüme, gölge, renk değişimleri
- **CSS Animasyonları**: Sayfa yüklenirken sıralı animasyonlar

## 📊 Kullanılan CSS3 Özellikleri

| Özellik | Kullanım Yeri | Açıklama |
|---------|---------------|----------|
| **CSS Units** | Tüm sayfa | px (kart genişliği), % (responsive), rem (fontlar) |
| **Width/Height** | .card (320px), .image-container (200px) | Sabit boyutlar |
| **Float** | .user-menu | Eski tip layout (demonstrasyon) |
| **Overflow** | .product-description | Uzun metin kontrolü |
| **Opacity** | .card:hover .product-image | Hover'da saydamlık |
| **Outline** | .buy-btn:focus | Erişilebilirlik |
| **Combinators** | .card > h2, .card:nth-child() | Gelişmiş seçiciler |
| **Box Shadow** | .card | Derinlik efekti |
| **Transform** | .card:hover | Scale büyütme |
| **Transition** | Tüm hover efektleri | Yumuşak geçişler |
| **CSS Variables** | :root | Renk yönetimi |
| **Flexbox** | .products, .header-container | Modern grid |


## 🎨 Ürün Çeşitliliği

1. **Akıllı Telefon X10** - "Yeni!" etiketi
2. **Kablosuz Kulaklık Pro** - "%20 İndirim" etiketi
3. **Akıllı Saat S5** - "Sınırlı Stok" etiketi
4. **Tablet T8 Pro** - "Kargo Bedava" etiketi
5. **Ultrabook X1 Carbon** - "Öne Çıkan" etiketi
6. **Oyun Konsolu Pro** - "Kampanyalı" etiketi

## 📱 Responsive Breakpoints

- **1200px+** : 3 kart yan yana (320px)
- **992px - 1200px** : 3 kart yan yana (300px)
- **768px - 992px** : 2 kart yan yana (280px)
- **480px - 768px** : 1 kart (350px max)
- **480px altı** : 1 kart (full width)

## ✨ Öne Çıkan Özellikler

2. **Renk Kodlu Etiketler**: Her kampanya farklı renkte
3. **Kombinator Örnekleri**:
   - Tek/çift kartlarda farklı border renkleri
   - İlk 3 kartta fiyat rengi değişimi
   - Son 3 kartta buton rengi farklı
4. **Footer İstatistikleri**: 6 ürün bilgisi gösterimi
5. **Sticky Header**: Kaydırmada sabit kalan başlık

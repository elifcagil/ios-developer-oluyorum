# 🌍 SwiftUI + UIKit + Google Maps: Modern iOS Harita Rehberi

> “Ben SwiftUI'cıyım.  
> Sen hâlâ sadece UIKit mi yazıyorsun?  
> UIKit mi SwiftUI mı? Neden ikisi birden olmasın?”  
> – Bir iOS Geliştiricisinin İkilemi

---

## ☄️ Giriş

Google Maps entegrasyonu mu dedin?  
Hem SwiftUI hem UIKit bir arada mı olsun?  
O zaman doğru yerdesin!

Bu repo, **Google Maps SDK**’sını hem SwiftUI hem de UIKit’le birlikte kullanmanın adımlarını pratik bir şekilde gösterir.

---

## 💡 Neden Bu Konu?

- 📌 Çünkü Google Maps hâlâ harita denince ilk akla gelen SDK  
- 🧩 UIKit ile yazılmış eski kodlarımız hâlâ hayatta  
- ✨ SwiftUI ise geleceğimiz  
- 🔄 Aralarında köprü kurmak artık zor değil  

---

## 🚀 Neler Öğreneceksin?

- ✅ Google Maps iOS SDK kurulumu ve API Key yönetimi  
- ✅ SwiftUI içinde UIKit öğelerini kullanmak  
- ✅ `UIViewRepresentable` ve `UIViewControllerRepresentable` ile köprü kurmak  
- ✅ Harita üzerine pin eklemek, kamerayı kontrol etmek  
- ✅ SwiftUI + UIKit karma projelerde dikkat edilmesi gereken konular  

---

## 🧠 Hedef Kitle

Sen:

- “Ben SwiftUI’ye başladım ama Google Maps UIKit’te kalmış!”  
- “UIKit projem var ama SwiftUI ekran da eklemem lazım.”  
- “API Key nasıl alınır, nerede tutulur, kimse anlatmıyor!”  

diyorsan, **buradayız ve beraber çözeceğiz.**

---

## 🔧 Proje Yapısı

| 📄 Dosya/Klasör           | Açıklama                                                                 |
|---------------------------|--------------------------------------------------------------------------|
| `ContentView.swift`       | SwiftUI arayüzünün giriş noktası. Haritayı burada çağırıyoruz.           |
| `GoogleMapView.swift`     | Google Maps’in UIKit tabanlı temsilcisi. `UIViewRepresentable` ile yazıldı. |
| `Google_MapsApp.swift`    | Uygulamanın başlangıç noktası. SwiftUI yaşam döngüsünü yönetiyor.        |

## 📚 Faydalı Kaynaklar

🧪 Özellikler

 SwiftUI + UIKit karma kullanımı
 Google Maps SDK entegrasyonu
 Custom MapView oluşturma
 Marker (pin) yerleştirme
 Kamera kontrolü
 Temiz, modüler kod yapısı
 
---

🤝 Katkıda Bulun

Pull request gönder 👨‍💻
Yıldızla ⭐

---

## ⚙️ Kurulum

```bash
git clone https://github.com/kullaniciadi/swiftui-uikit-googlemaps.git
cd swiftui-uikit-googlemaps
open MapsIntegration.xcodeproj


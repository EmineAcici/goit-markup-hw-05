# GoIT Markup Homework 05 - WebStudio (Forms & Modals)

Bu proje, GoIT Full Stack Developer eğitimi kapsamında hazırlanan **WebStudio** projesinin beşinci aşamasıdır. Bu bölümde, kullanıcı etkileşiminin merkezi olan modal pencereler, abonelik formları ve gelişmiş form giriş (input) tasarımları üzerinde çalışılmıştır.

## 🚀 Proje Gereksinimleri ve Teknik Standartlar

Bu çalışma, belirtilen tüm teknik kriterlere (A1-D6) tam uyumlu olarak geliştirilmiştir:

### 🏗️ Proje Altyapısı (A Serisi)
- **CSS Yönetimi:** Tüm stiller `css/styles.css` dosyasında merkezi olarak toplanmıştır.
- **Kod Kalitesi:** **Prettier** ile biçimlendirilmiş, mizanpaj verilerine sadık kalınmış ve `modern-normalize` kullanılmıştır.

### 🪟 Modal Pencere Mimarisi (B Serisi)
- **Backdrop:** Tarayıcı alanının %100'ünü kaplayan, sabitlenmiş ve yarı saydam arka plan (backdrop) tasarımı tamamlanmıştır.
- **Konumlandırma:** Modal pencere, ekranın dikey ve yatay merkezine tam olarak yerleştirilmiştir.
- **Durum Yönetimi:** Modal ve backdrop başlangıçta gizlenmiş durumdadır. `.is-open` sınıfı eklendiğinde görünür hale gelmektedir.
- **Kapatma Butonu:** Sağ üst köşede yer alan kapatma butonu tasarım standartlarına göre özelleştirilmiştir.

### 📝 Form ve İşaretleme Standartları (C Serisi)
- **Semantik Formlar:** Footer içindeki bülten abonelik formu ve modal içindeki başvuru formu semantik etiketlerle yapılandırılmıştır.
- **Erişilebilirlik:** - Tüm input öğeleri açıklayıcı `name` niteliklerine sahiptir.
  - Her giriş alanının (input) ilişkili bir `<label>` öğesi bulunmaktadır.
  - E-posta alanları için doğru `placeholder` değerleri tanımlanmıştır.
- **Vektör Yönetimi:** Formlarda kullanılan tüm yeni simgeler (input ikonları, tik işareti vb.) `icons.svg` sprite dosyasına dahil edilmiştir.

### 🎨 Form Tasarımı ve İnteraktivite (D Serisi)
- **Giriş Alanları:** Input odaklandığında (focus), çerçeve ve simge renk değişimi tasarım mizanpajına uygun şekilde uygulanmıştır.
- **Özel Checkbox:** Kullanıcı sözleşmesi onay kutusu (checkbox) orijinal haliyle gizlenmiş; SVG sprite'dan alınan tik işareti ile manuel olarak yeniden tasarlanmıştır.
- **Animasyon ve Geçişler:**
  - Tüm `:hover` ve `:focus` efektleri için **250ms** süre ve **cubic-bezier(0.4, 0, 0.2, 1)** zaman fonksiyonu kullanılmıştır.
  - Form submit butonları `type="submit"` olarak ayarlanmış ve etkileşimli stiller eklenmiştir.

## 🛠️ Kullanılan Teknolojiler
* **HTML5 & CSS3**
* **SVG Sprites** (Form İkonları)
* **CSS Modal & Backdrop Techniques**
* **Custom Form Elements** (Özelleştirilmiş Checkbox)

## 🔗 Canlı Önizleme
Projenin etkileşimli formlarını aşağıdaki bağlantıdan inceleyebilirsiniz:
[GitHub Pages Üzerinden Görüntüle](https://emineacici.github.io/goit-markup-hw-05/)

---
*Hazırlayan: [Emine Acıcı](https://github.com/EmineAcici)*

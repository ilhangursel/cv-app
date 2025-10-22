# Kişisel CV Web Sitesi — Ergün Erez

Bu proje, sağladığınız ekran görüntüsüne (CV / kişisel web sitesi) benzer basit, statik bir web sitesi sunar.

Dosyalar
- `index.html` — Ana sayfa içerikleri ve HTML yapısı (Türkçe).
- `styles.css` — Sayfayı gösteren temel stiller.
- `assets/profile.svg` — Profil için SVG yer tutucu.

Nasıl çalıştırılır
Yerel olarak açmak için en kolay yol basit bir HTTP sunucusu çalıştırmaktır. Eğer Python 3 kuruluysa, proje kökünden (c:\repos\cv-app) şu komutu çalıştırın:

```powershell
python -m http.server 8000
```

Ardından tarayıcınızda `http://localhost:8000` adresini açın.

Öneriler / Sonraki adımlar
- Gerçek bir profil fotoğrafı ekleyin: `assets/profile.svg` yerine `assets/me.jpg` koyup `index.html` içinde güncelleyin.
- Yazı tiplerini özelleştirin veya Google Fonts ekleyin.
- PDF olarak yazdırma/stil ekleyin (print CSS).
- İsterseniz renk paletini ya da düzeni istediğiniz gibi değiştirebilirim.


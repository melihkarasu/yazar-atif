# Akademik Yazar & Tüm Yayın Atıf Röntgeni (Standalone Edition)

Bir akademisyenin tüm yayınlarını, H-indeksi/i10-indeksi metriklerini, yıllara göre atıf dağılımını ve tüm yayınlarına gelen atıfların birleşik listesini (Scopus/Core, Crossref, PubMed ayrımıyla) tablo halinde inceleyin ve CSV/BibTeX olarak indirin.

- **Canlı Demo (GitHub Pages):** https://melihkarasu.github.io/yazar-atif/
- **Ana Proje (Monorepo):** [melihkarasu/VibeCodedApps](https://github.com/melihkarasu/VibeCodedApps)

## Mimari & Gizlilik Özellikleri
- **Sıfır Backend (Zero-Backend):** Tamamen tarayıcı üzerinde çalışır; kullanıcı verileri VibeRuntime üzerinden yalnızca localStorage içinde saklanır.
- **KVKK & GDPR Uyumu:** Google Fonts CDN veya 3. taraf takip betiği içermez; tüm fontlar (vendor/fonts/*.woff2) yerel olarak paketlenmiştir.

## Lokal Çalıştırma
```bash
npx serve .
```

# zenithdiag.com.tr — yayın deposu

Bu depo **otomatik oluşturulur**: yalnızca derlenmiş siteyi (`public/`) ve yayın bilgilerini (`_ops/`) içerir. Kaynak kod ayrı
ve özel bir depodadır. Elle düzenlemeyin.

- `main` — sunucudaki yayın betiğinin kurduğu son sürüm
- `seed` — yalnızca ilk kurulumda (veritabanı boşken) yüklenen başlangıç içeriği
- `.github/workflows/yayin.yml` — her 5 dakikada bir kaynak ve içerik değişikliğini kontrol eder, derler, paketler ve gönderir

# AALabs paket deposu

Bu depo AALabs uygulamalarının kurulum paketlerini tutar. Paketleri **AALabs App Store** indirir ve kurar; elle indirmeye gerek yoktur.

- `paketler/<Id>/<Id>_<sürüm>_NNofMM.part` — bir uygulama sürümünün zip paketi, parça parça.
- Index (hangi uygulamanın hangi sürümü var) Google Drive'daki `index.json` dosyasındadır. Index'teki her parça adresi bir commit'e sabittir ve SHA-256 ile denetlenir.
- Her uygulamanın güncel sürümü ve 2 önceki sürümü tutulur.

Depoya yalnız Claude, yayın betiğiyle (`yayinla.py`) yazar.

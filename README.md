# Batuhan-Enes-Portfolio

Unity ve C# odaklı, mobil ve PC platformları için optimize edilmiş projelerimden oluşan profesyonel vitrinimdir. Özellikle **Clean Code**, **Yazılım Mimarileri** ve **Multiplayer Sistemler** üzerine yoğunlaşmaktayım.

---

## Steam & PC Projeleri
Multiplayer Mimarisi: Unity Netcode altyapısını kullanarak 5 oyuncuya kadar destek veren, düşük gecikmeli (low-latency) ve hile korumalı sunucu-tabanlı bir ağ yapısı geliştirdim.

Ekip İçi Yazılım Standartları: Ortak kod tabanında (shared codebase) SOLID prensiplerini ve mimari desenleri (Design Patterns) uygulayarak, projenin sürdürülebilirliğini ve ekip içi entegrasyonu 
sağladım.

Steam Entegrasyonu: Steamworks API süreçlerine aşinalık kazanarak, lobi yönetimi ve oyuncu eşleştirme (matchmaking) sistemlerinin temellerini kurguladım.

Problem Çözme ve Debugging: Çok oyunculu ortamlarda ortaya çıkan ağ kaynaklı (latency, packet loss) bug'ların tespiti ve çözümü için gelişmiş debugging teknikleri kullandım.


##  Mobil Serisi 
2D mantık ve zeka oyunlarını kapsayan, market süreçleri tamamlanmış projelerdir. (App store ve Play store)

### Grid-X 
Dinamik Grid Sistemi: Bölüm aşamasına göre (Stage) otomatik ölçeklenen (5x5 ile 11x11 arası) ve performans kaybı olmadan binlerce düğüm etkileşimini yöneten bir grid yapısı geliştirdim.

UX Odaklı Girdi Yönetimi: Input.mousePosition verilerini Lerp ve Raycast süreçlerinden geçirerek, grid üzerinde takılma hissi yaratmayan "Smooth Highlight" mekanizmasını programladım.

Veri Odaklı Seviye Tasarımı (Data-Driven): Seviye verilerini LevelData üzerinden merkezi bir Dictionary yapısında toplayarak, binlerce bölümü tek bir noktadan yönetebilen esnek bir sistem kurdum.

###  GalaxySudoku
Karmaşık Algoritma Geliştirme: Sudoku bulmacaları için rekürsif Backtracking algoritması kullanarak hızlı bir çözücü ve benzersiz çözüm doğrulayıcı sistem tasarladım.

Esnek Veri Serilizasyonu: Farklı JSON formatlarındaki seviye verilerini (puzzle_rows, solution_rows) dinamik olarak parse eden ve oyun içi grid yapısına (Unflatten) dönüştüren bir veri katmanı inşa ettim.

Oyun Mantığı ve Mimari: SubGrid ve Cell sınıfları üzerinden, 81 hücreli karmaşık bir oyun alanını optimize edilmiş Singleton bir GameManager ile merkezi olarak yönettim.

Zorluk Analizi ve İpucu Algoritması: Kullanıcıya en stratejik hamleyi sunan, aday sayı analizi yapan (AllowedForCell) ve otomatik hata denetimi sağlayan yardımcı sistemler geliştirdim.


###  Words (Multiplayer)
Mirror mimarisi ve **Firebase Realtime Database** kullanılarak geliştirilmiş, kelime bulmaca tabanlı çok oyunculu deneyim.


### ColorSoft 
Renk Gradyan Algoritması: Dört köşe renginden tüm grid renklerini hesaplayan dinamik renk interpolasyon sistemini geliştirdim.

Data-Driven Level Design: ScriptableObject kullanarak kolayca genişletilebilir ve optimize edilmiş bir seviye oluşturma sistemi kurdum.

Gelişmiş UX Animasyonları: DOTween ile hücrelerin karıştırılması ve kullanıcı hamlelerinin görsel geri bildirimlerini asenkron bir yapıda yönettim.

Oyun Mantığı ve State Check: Grid üzerindeki her hamle sonrası renk dizilimini kontrol eden ve kazanma durumunu (CheckWin) denetleyen algoritmayı optimize ettim.

### NumberLink
Prosedürel Grid Sistemleri: Veri setinden (LevelData) dinamik olarak oyun alanını oluşturan ve boşlukları otomatik kompanse eden bir grid yönetim sistemi geliştirdim.

Gelişmiş Hücre Etkileşim Mimarisi: Hücreler arası bağlantı sayısını (Bridges logic) takip eden ve Dictionary veri yapıları ile performanslı kenar yönetimi sağlayan bir sistem inşa ettim.

UX Odaklı Girdi Analizi: Kullanıcının sürükleme (drag) hareketlerinden vektörel yön analizi yaparak dinamik görsel efektler (Highlight stretching) oluşturan bir girdi sistemi programladım.


---

##  Teknik Yetkinlikler

### Geliştirme 
- **Engine:** Unity Engine (Gelişmiş 2D & 3D Projeler).
- **C#:** SOLID prensipleri, Design Patterns ve "Readable Code" felsefesi.
- **Networking:** Unity Netcode, Mirror, Firebase.


### Tasarım & Modelleme (Design & Art)
- **2D UI/UX:** Figma, Adobe Illustrator (Neon, Modern UI, gibi çoklu tasarımlar).
- **3D Art:** Blender (Low-poly, çevre modelleme, açık dünya haritalamaları).

---

# Dosya Paylaşımı ve Yönetim Sistemleri

Bu proje, **Dosya Paylaşımı ve Yönetim Sistemlerinin Yapılandırılması** konusunu ele almaktadır. Proje kapsamında, Linux tabanlı sistemler için yaygın olarak kullanılan **Network File System (NFS)** ve farklı işletim sistemleri arasında dosya paylaşımına olanak sağlayan **Samba** sistemleri incelenmiştir.

---

## 📚 İçerik

- **Network File System (NFS):**
  - NFS'nin temel işlevleri
  - Avantajları ve dezavantajları
  - Güvenlik önlemleri
- **Samba:**
  - Sambanın işleyişi ve kullanım alanları
  - Avantajları ve dezavantajları
  - Güvenlik önlemleri ve performans ölçütleri
- **NFS ve Samba Karşılaştırması:**
  - Özgün tasarım farkları
  - Paylaşılan kaynaklar
  - İstemci-istemci iletişimleri

---

## 🛠️ Projede Kullanılan Teknolojiler

- **NFS (Network File System):** Linux tabanlı sistemlerde dosya ve veri paylaşımı için kullanılır.
- **Samba:** Farklı işletim sistemleri arasında dosya paylaşımı sağlar.
- **Linux:** Ana işletim sistemi olarak kullanılmıştır.

---

## 🚀 Kurulum ve Çalıştırma

1. **NFS Kurulumu:**
   - Linux dağıtımınızda NFS sunucusunu yapılandırın.
   - Paylaşılacak dosya ve dizinleri belirtin.
   - `nfs-kernel-server` servisini başlatın.
   
2. **Samba Kurulumu:**
   - Samba'yı yükleyin: `sudo apt install samba`
   - `smb.conf` dosyasını düzenleyerek paylaşılan dizinleri tanımlayın.
   - Samba servisini başlatın: `sudo service smbd start`
   
3. **Sistem Testi:**
   - NFS ve Samba yapılandırmalarını doğrulamak için istemcilerden bağlantı sağlayın.

---

## ⚡ Özellikler

- **Kolay Yönetim:** Merkezi depolama ve uzaktan erişim imkanı.
- **Güvenlik Önlemleri:** Dosya paylaşımı sırasında verilerin güvenliğini sağlamak için yapılandırılmıştır.
- **Performans Ölçümleri:** Dosya paylaşımı hızını optimize etmek için test edilmiştir.

---

## 📊 Performans ve Güvenlik

- **NFS:** Basit ve hızlı yapılandırma imkanı, ancak güvenlik için ek önlemler gereklidir.
- **Samba:** Genişletilebilirlik ve farklı işletim sistemleriyle uyum, performans ayarlarıyla optimize edilebilir.

---

## 👥 Katkıda Bulunanlar

- Nasif Can Yavuz - 201401019
- Ömer Polat - 201401057
- Doğukan Erzurum - 201401023
- Ramazan Serhat Uygun - 201401049


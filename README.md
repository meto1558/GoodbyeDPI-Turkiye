# DPI nedir?

DPI, bir ağ üzerinden geçen veri paketlerini inceleyerek bu paketlerin içeriği hakkında detaylı bilgi elde etmeyi sağlar. Geleneksel ağ denetim teknikleri, yalnızca bir veri paketinin başlık (header) bilgilerini kontrol ederken, DPI paketlerin içeriğini de analiz eder.

# GoodbyeDPI nedir?

GoodbyeDPI, internet sansürünü ve trafiği engelleme girişimlerini aşmak için kullanılan bir yazılımdır. Bu araç, Deep Packet Inspection (DPI) adı verilen ve internet servis sağlayıcılarının (ISS) veri paketlerini analiz ederek belirli web sitelerine veya hizmetlere erişimi kısıtlamasını sağlayan bir teknolojiyi atlatmayı amaçlar. Bu fork/forklar Türkiye için yeniden dizayn edilmiştir.

# Bu araca neden ihtiyaç var?

Türkiye'de ki erişim engellerini aşmak için genelde DNS değiştirmek veya VPN açmak işe yarıyor. Ancak bazı internet sağlayıcıları (Turk Telekom, Turkcell vb.) DNS değişiminden etkilenmiyor, çünkü DPI teknolojisini kullanıyorlar. VPN'de bir alternatif ancak genelde lag sorunları yaşatabiliyor. Bu yüzden bu araç oldukça işlevsel.

## Nasıl kullanılır?
- [goodbyedpi-0.2.3rc3-2_turkiye.rar](https://github.com/meto1558/GoodbyeDPI-Turkiye/releases/download/v0.2.3/goodbyedpi-0.2.3rc3-2_turkiye.rar) dosyasını indirin.
- service_install_turktelekom.cmd dosyasını **yönetici** olarak çalıştırın.
- Tek seferlik çalıştırmak istiyorsanız sadece turktelekom.cmd'yi yine **yönetici** olarak çalıştırın.

## Tek seferlik ve servis arasındaki fark nedir?
- Servis olarak kullanırsanız bir Windows servisi olarak kurulacaktır, bu sayede her sistem açıldığında otomatik olarak aktif hale gelecektir.
- Tek seferlikte adından da anlaşılacağı üzere böyle bir durum söz konusu değil.

**Eğer bu fork çalışmazsa, başka bir dostumuzun oluşturduğu şu forku kullanabilirsiniz:** https://github.com/cagritaskn/GoodbyeDPI-Turkey

> [!NOTE]
> Türkiye'de yasak olan farklı sitelere de VPN'siz erişim sağlamaktadır (Roblox gibi).

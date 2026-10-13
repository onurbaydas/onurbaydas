<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Onur%20Baydaş&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Sistem%20%26%20Altyap%C4%B1%20M%C3%BChendisi&descAlignY=58&descSize=18&animation=fadeIn" alt="Onur Baydaş" width="100%" />
</p>

<p align="center">
  <a href="https://onurbaydas.online">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3500&pause=900&color=4FC3F7&center=true&vCenter=true&width=640&lines=On-prem+infrastructure+%C2%B7+design+%26+operations;Virtualization+%C2%B7+Software-Defined+Storage+%C2%B7+HCI;GPU+Partitioning+%C2%B7+HPC+Job+Scheduling;Container+Security+%C2%B7+Policy-as-Code;Ger%C3%A7ek+olaylardan+teknik+yaz%C4%B1lar" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://onurbaydas.online"><img src="https://img.shields.io/badge/Blog-onurbaydas.online-0f2027?style=for-the-badge&logo=readdotcv&logoColor=4FC3F7" alt="Blog" /></a>
  <a href="https://onurbaydas.online/index.xml"><img src="https://img.shields.io/badge/RSS-Abone%20ol-2c5364?style=for-the-badge&logo=rss&logoColor=FFA500" alt="RSS" /></a>
  <img src="https://komarev.com/ghpvc/?username=onurbaydas&style=for-the-badge&color=203a43&label=Profil+G%C3%B6r%C3%BCnt%C3%BClenme" alt="Profile views" />
</p>

---

## 👋 Merhaba

Türkiye'de çalışan bir **sistem ve altyapı mühendisiyim**. 2024'ten bu yana bir sistem entegratöründe on-prem altyapı tasarlıyor, kuruyor, işletiyor ve sorun gideriyorum: yönetilen bir bulut servisine yaslanamadığınız, donanımdan depolamaya, kimlikten iş zamanlamaya kadar **her katmanın sizin sorumluluğunuzda olduğu** ortamlar.

Kurumsal müşteriler, araştırma laboratuvarları ve yapay zekâ iş yükleri için çok kullanıcılı GPU platformları, hyperconverged cluster'lar, yedekleme ve izleme altyapıları üzerinde çalışıyorum. Bilgisayar mühendisliği eğitimimi tamamlamak üzereyim.

```yaml
onur:
  rol: Systems & Infrastructure Engineer
  deneyim: 2024'ten beri on-prem altyapı (design · deployment · operations)
  konum: Türkiye 🇹🇷
  eğitim: Bilgisayar Mühendisliği (mezuniyete yakın)
  odak: [on-prem, virtualization, gpu-infrastructure, hpc, container-security, observability]
  şu_an:
    - Multi-tenant GPU cloud tasarımı: Kubernetes-native HPC scheduling + fractional GPU sharing
    - GPU destekli VDI: virtual GPU ile passthrough'suz paylaşımlı sanal masaüstü (POC)
    - Backup monitoring ürünü: virtual appliance dağıtımı, imzalı lisanslama, gerçek ortam testleri
    - Teknik yazarlık: canlı ortam olaylarından Türkçe/İngilizce makaleler
  öğreniyor: [Kubernetes, GPU software stack, cloud architecture]
  hedef: AI Infrastructure · GPU Operations · HPC
  ilgi: [agentic AI workflows, local LLMs, transformers from scratch, offensive security]
```

## 🛠️ Neler Üzerinde Çalışıyorum

| Alan | Detay |
| :--- | :--- |
| 🖥️ **Virtualization & Storage** | Cluster tabanlı virtualization, software-defined storage, hyperconverged infrastructure (HCI), enterprise NAS ve ZFS tabanlı depolama |
| 🎮 **GPU Altyapısı** | Yapay zekâ ve araştırma iş yükleri için GPU sunucuları ve cluster'ları, GPU partitioning ve virtual GPU, HPC job scheduling, stres testi ve driver/framework uyumluluğu |
| 👥 **Çok Kullanıcılı Platformlar** | Paylaşımlı Linux iş istasyonları: kullanıcı izolasyonu, rezervasyon ve kaynak yönetimi, container erişim kontrolü, günlük operasyon |
| 🔐 **Container Güvenliği** | Paylaşımlı makinelerde container runtime'ı kısıtlamak, policy-as-code ile authorization, cross-user izolasyon açıkları |
| 🪪 **Kimlik & Erişim** | Directory services ve identity management, Kerberos ile kimlik doğrulama, network home directories, PAM entegrasyonu |
| 💾 **Backup & DR** | Hyperconverged backup, deduplication backup appliance'ları, yedekleme izleme ve raporlama |
| ♻️ **High Availability** | Cluster resource management, block-level replication, active/passive servis failover |
| 📈 **Observability** | Metrics, centralized logging, alerting ve dashboard'lar; merkezi syslog toplama |
| 🔧 **Donanım & Yaşam Döngüsü** | Rack sunucu kurulumu, out-of-band management (BMC), RAID controller ve disk arızası analizi, vendor support süreçleri |
| 🌐 **Network & Security** | Next-generation firewall yönetimi, segmentasyon, yönetim ağı tasarımı |

## 🚀 Öne Çıkan Çalışmalar

<details open>
<summary><b>🧪 Çok kullanıcılı GPU iş istasyonu platformu</b></summary>

<br/>

Bir araştırma laboratuvarındaki **20 GPU'lu Linux iş istasyonu** için uçtan uca rezervasyon ve yönetim platformu tasarlayıp işlettim, ardından devrettim.

- **Uygulama:** REST API backend, relational database, modern web frontend
- **Kimlik:** Directory service + Kerberos, ağ üzerinden ev dizinleri, PAM tabanlı oturum kontrolü
- **Container:** Private container registry, kullanıcının kendi UID'siyle çalışan container'lar, erişim policy'leri
- **Operasyon:** Configuration management ile toplu kurulum, metrics ve dashboard'lar
- **Dokümantasyon:** Kapsamlı sistem dokümanı ve 39 maddelik *known issues* envanteri (izolasyon, kimlik doğrulama, veri kalıcılığı)

</details>

<details>
<summary><b>💾 Backup monitoring ürünü</b></summary>

<br/>

Hyperconverged platformlar ve backup appliance'lar için yedekleme izleme ürünü.

- Dış bağımlılık olmadan, yalnızca standart kütüphaneyle Python
- Virtual appliance ve paket olarak dağıtım, imzalı yıllık lisans
- Kurumsal müşteride canlı kullanımda, 2.x sürüm serisinde aktif geliştirme

</details>

<details>
<summary><b>☁️ Multi-tenant GPU cloud tasarımı</b></summary>

<br/>

Yeni nesil GPU sunucuları için, kullanıcıların on-demand GPU ortamı açabildiği **otomatik ve çok kullanıcılı** bir platform mimarisi: Kubernetes üzerinde HPC scheduling, fractional GPU sharing ve kaynak kotaları.
</details>

<details>
<summary><b>🖥️ GPU destekli VDI laboratuvarı</b></summary>

<br/>

20 istemcilik bir eğitim laboratuvarı için virtual GPU tabanlı sanal masaüstü altyapısı. GPU passthrough olmadan paylaşımlı GPU kullanımı, proof-of-concept aşamasında.
</details>

<details>
<summary><b>🔬 Araştırma projeleri</b></summary>

<br/>

- **P2P şifreli mesajlaşma:** Post-quantum key exchange ve Double Ratchet tabanlı uçtan uca şifreleme, merkeziyetsiz ağ katmanı (Rust)
- **Out-of-band management cockpit:** Farklı üreticilerin BMC konsollarını tek arayüzde toplayan masaüstü uygulaması (prototip)

</details>

## 🧯 Sahadan Notlar

Canlı ortamda çözdüğüm problemlerden bazıları:

- 🔁 **HA mail altyapısı:** 3 node'lu HCI cluster üzerinde cluster resource manager + block-level replication ile active/passive failover, fencing kısıtı olan ortamda tasarım
- 💥 **Host çökmesi analizi:** Hyperconverged node'da RAID controller kaynaklı PCIe hatalarının log analizi ve vendor support case hazırlığı
- 🧩 **Appliance taşıma:** Vendor backup appliance'ını farklı bir hypervisor'a kurmak (UEFI firmware, legacy boot disk, CPU model ayarları)
- 🪵 **Sessiz log kaybı:** Merkezi syslog kurulumunda eski forwarding sözdiziminin yeni dağıtımlarda hata vermeden çalışmaması
- 🛟 **Firmware kurtarma:** Açılmayan sunucuyu BMC flash recovery ile geri getirme
- 🗄️ **Backup appliance arızası:** Disk arızası, RAID6 reconstruction ve bellek yerleşimi analizi
- 🔒 **Hypervisor sorunları:** Sanal disk kilitleri ve takılan yedekleme kuyrukları
- 🔥 **Yeni nesil GPU doğrulama:** Stres testi script'i ve driver/ML framework uyumluluğu
- 📊 **Monitoring stack:** Metrics, logs, alerting ve reverse proxy ile uçtan uca izleme
- ✉️ **Migration planlama:** Hosted e-posta servisinden cloud productivity suite'e geçiş planı

## 🧰 Uzmanlık Alanları

<p align="center">
  <img src="https://img.shields.io/badge/Virtualization-0f2027?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Software--Defined%20Storage-203a43?style=for-the-badge" />
  <img src="https://img.shields.io/badge/HCI-2c5364?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ZFS%20Storage-0f2027?style=for-the-badge" />
  <img src="https://img.shields.io/badge/High%20Availability-203a43?style=for-the-badge" />
  <br/>
  <img src="https://img.shields.io/badge/GPU%20Computing-2c5364?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GPU%20Partitioning-0f2027?style=for-the-badge" />
  <img src="https://img.shields.io/badge/HPC%20Scheduling-203a43?style=for-the-badge" />
  <img src="https://img.shields.io/badge/VDI-2c5364?style=for-the-badge" />
  <br/>
  <img src="https://img.shields.io/badge/Containerization-0f2027?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kubernetes-203a43?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Policy--as--Code-2c5364?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Configuration%20Management-0f2027?style=for-the-badge" />
  <br/>
  <img src="https://img.shields.io/badge/Linux%20Administration-203a43?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Identity%20%26%20Access%20Mgmt-2c5364?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Network%20Security-0f2027?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backup%20%26%20DR-203a43?style=for-the-badge" />
  <br/>
  <img src="https://img.shields.io/badge/Observability-2c5364?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Server%20Hardware-0f2027?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-203a43?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Bash-2c5364?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Technical%20Writing-0f2027?style=for-the-badge" />
</p>

## ✍️ Son Blog Yazılarım

> Canlı ortamda gerçekten karşılaştığım sorunları yazıyorum: sessiz hatalar, yanıltıcı dokümantasyon ve dokümanın söylemediğini kaynak kodun nasıl söylediği.

<!-- BLOG-POST-LIST:START -->
- [Bir Kullanıcı, İki UID: Domain&#39;e Bağlı TrueNAS&#39;ta NFSv4, Kerberos ve Docker](https://onurbaydas.online/posts/nfs-uid-mismatch/)
- [OPA ile Docker Authorization: Sessiz Fail-Open ve Canlı Ortamdan Dersler](https://onurbaydas.online/posts/docker-authz-opa/)
<!-- BLOG-POST-LIST:END -->

<p align="right"><a href="https://onurbaydas.online">Tüm yazılar →</a></p>

## 📊 GitHub İstatistikleri

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=onurbaydas&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&locale=tr" alt="GitHub Stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=onurbaydas&theme=tokyonight&hide_border=true&locale=tr" alt="GitHub Streak" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/onurbaydas/onurbaydas/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/onurbaydas/onurbaydas/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/onurbaydas/onurbaydas/output/github-snake.svg" />
  </picture>
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%" />
</p>

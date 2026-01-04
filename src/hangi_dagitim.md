# Hangi Linux Dağıtımını Kullanmalıyım?

**Bu rehber düzenlenme aşamasındadır**

Çoğu vakit her Linux dağıtımı her işinizi görür ancak bu rehberde hangi Linux dağıtımı hangi konuda öne çıkar, hangi konuda hangisine ihtiyaç duyarız bunları ele alacağız.

Uyarı!
Bu rehberde sadece büyük bir topluluk veya şirketler tarafından desteklenen GNU/Linux dağıtımlarını ele alacağız. Küçük ekiplerin yönettiği ve sürdürülebiliriği pek yüksek olmayan GNU/Linux dağıtımlarını değerlendirmeyeceğiz. Bu, o dağıtımlar kötü olduğu için değil; profesyönel çalışmak isteyen insanların işlerini sürdürülebilir hale getirmesi amacıyla yapılmıştır.

# SSS
***Ben son kullanıcıyım, gündelik hayatımda Linux kullanmak istiyorum. Ne tercih etmeliyim?***
<br>Fedora'yı öneririm. Ancak Manjaro ve Ubuntu da güzel bir tercihtir.

***Ben AI ile uğraşıyorum, hangisini tercih etmeliyim?***
<br>Çoğu AI aracı için Ubuntu uygun olacaktır.

***Sunucum için hangi Linux dağıtımını tercih etmeliyim?***
<br>Büyük bir sunucusu ise RHEL, genel kullanım için Debian veya Ubuntu Server

***Siber güvenlik ile uğraşıyorum, ne önerirsin?***
<br>Kali Linux veya Debian + gerekli toollar

# Dağıtımlara Detaylıca Bakalım

## 1. Redhat Enterprise Linux (RHEL)
Redhat Enterprise Linux (veya kısaca RHEL), işletmeler ve devletler tarafından en çok kullanılan ve desteklenen GNU/Linux dağıtımıdır. Paketleri RPM (Redhat Package Manager) ile yönetir. RHEL, hem topluluğa yaptığı katkı hem de devamlı destekl alıyor olmasından ötürü geniş bir uygulama yelpazesine sahiptir. RHEL'in arkasında büyük teknoloji devi IBM vardır. RHEL, dnf paket yöneticisini kullanır. Sunucularınızda RHEL'i kullanmayı tercih edebilirsiniz

### Fedora GNU/Linux
Fedora, Redhat'in kullanıcı versiyonudur. Doğrudan Redhat tarafından desteklenir ve finanse edilir. RHEL için dediğimiz her şey Fedora için de geçerlidir ve Fedora, RHEL'e ek olarak kullanıcılara yöneliktir. Paketleri her zaman günceldir ve topluluk tarafından büyük ilgi görür. Ayrıca, Linux kernelinin yaratıcısı olan Linus Torvalds da Fedora'yı kullanır. Fedora, RHEL gibi dnf paket yöneticisini kullanır. Eğer GNU/Linux'u masaüstü cihazınızda kullanmak istiyorsanız Fedora'ya yönelebilirsiniz

## 2. Debian GNU/Linux
Debian, debian vakfı tarafından yönetilen kararlılık ve stabilite odaklı bir Linux dağıtımıdır. Debian, büyük oranda sunucularda kullanılır. Örneğin Google, kendi sunucularında ve Google Stadia projesinde Debian kullanmaktadır. 

Debian, `apt` paket yöneticisini ve `deb` paket yönetim sistemini kullanır.

### Ubuntu
Ubuntu debian tabanlı bir proje olsa da orjinal Debian'dan 21 yıl önce ayrılmıştır ve günümüzde paketleri paketleme ve açma biçimleri dışında pek bir ortak noktaları yoktur. Nvidia, yapay zeka araçlarını Ubuntu için yazar ve çoğu son kullanıcı odaklı GNU/Linux dağıtımı Ubuntuyu çatal alır. Eğer GNU/Linux'u masaüstü cihazınızda kullanmak istiyorsanız Ubuntu'ya yönelebilirsiniz

Ubuntu, Debian'a ek olarak `snap` isimli evrensel bir paket yöneticisi de kullanır

### Kali Linux
Kali Linux bir Debian çatılıdır ve Ubuntu'nun aksine orjinal Debian projesine bağımlıdır ve onu takip eder. Kali, özelleştirilmiş bir arayüz ve siber güvenlik araçları ile birlikte gelir. Kali, saldırı araçlarını tercih etse de kali purple isimli çatalları koruma araçlarına yöneliktir.

## 3. Arch Linux
Arch Linux, yuvarlanan ve son kullanıcı odaklı bir Linux dağıtımıdır. Sunucular için iyi bir seçenek değildir. Ancak Arch Linux (ve Arch Linux tabanlı dağıtımlar), geniş bir user-repository'e sahip olduğu için bir son kullanıcı olarak Arch Linux tabanlı dağıtım tercih edebilirsiniz

Arch Linux, `pacman` paket yöneticisini kullanır. User repository için AUR kullanılır ve AUR'dan yazılım indirmek için AUR yardımcıları kullanılır. (bkz. [AUR Helpers](https://wiki.archlinux.org/title/AUR_helpers))

### Manjaro
Manjaro, Arch Linux tabanlı bir Linux dağıtımıdır. Manjaro, dönemin vizyoner bir dağıtımı olduğu için şirketleşmeyi başarmıştır. Arch Linux'un aksine yarı-yuvarlanan bir GNU/Linux dağıtımıdır. Paketler bir süre test edilir ve öyle dağıtılır. Manjaro, son kullanıcı için iyi bir tercihtir.

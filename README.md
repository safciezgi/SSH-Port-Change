# SSH PORTU NASIL DEĞİŞTİRİLİR
İlk olarak değişiklik yapmak istediğiniz sunucu ile SSH bağlantısı kurun. Bunu sağlamak için,  
 
```
ssh root@{host}
```
komutu ile aşağıdaki örnekteki gibi bağlantı sağladığınızdan emin olun:    


Gerekli düzenlemeleri yapmamız için konfigürasyon dosyasına erişmemiz gerekecek. Bunun için terminalde,  
```
nano /etc/ssh/sshd_config
```
komutunu girmemiz gerek.
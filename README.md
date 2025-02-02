# Network Automation

Bu proje, bir ağdaki fiziksel veya sanal cihazların yönetimini, test edilmesini ve diğer ağ işlemlerini otomatikleştirmeyi amaçlamaktadır.

## Kullanılan Teknolojiler

- **Programlama Dili:** Python
- **Sanallaştırma:** VirtualBox
- **Web Framework:** Flask
- **Veritabanı:** PostgreSQL
- **Ağ Protokolleri:** Paramiko, SSH Protokolü, Ngrok

## Açıklama

- VirtualBox'a **3 adet sanal makine** kurulur.
- Sanal makineler arasında **SSH protokolü** ve **Paramiko** yardımıyla iletişim sağlanır.
- Bağlandığımız makinelerdeki gerekli bilgilere (ekte mevcut) komutlarla ulaşıp **veritabanına kaydedilir**.
- **Flask** ile API'ler oluşturularak **lokalde çalıştırılır**.
- **Ngrok** kullanılarak API'ler **internete açılır**.
- **Flutter** ile mobil tasarımı yapılmıştır.

## Dağıtım

Projeyi çalıştırmak için aşağıdaki komutu kullanabilirsiniz:

```sh
flask run
```

## Veritabanı
![schema](https://github.com/user-attachments/assets/16faa0e0-8ff5-4728-ae60-4c420e0df321)

## Belgelendirme

[Sistem Tasarım Dökümanı (SDD) ](https://github.com/user-attachments/files/18632867/sdd_networkautomation.pdf)

#Network Automation

Projenin adından da anlaşılacağı üzere, bir ağdaki fiziksel veya sanal cihazların yönetimi, test edilmesi gibi network işlemlerini otomatikleştirmek amaçlanmıştır.

##Kullanılan Teknolojiler
Python , VirtualBox , Flask , PostgreSQL
Paramiko, SSH Protokolü, Ngork

**Açıklama**

*VirtualBox'a 3 tane sanal makine kuruyoruz.
*Sanal makineler arasında SSH protokolü ve paramiko yardımıyla iletişim sağlıyoruz.
*Bağlandığımız makinelerdeki gerekli bilgilere (ekte mevcut) komutlarla ulaşıp veritabanımıza kaydediyoruz.
*Flask ile api'leri oluşturup local'de çalışmasını sağlıyoruz.
*ngrok ile localden çıkarıp, web'e aktardık.
*Flutter ile mobil tasarımını yapıyoruz.

#Dağıtım

Bu projeyi dağıtmak için çalıştırın

  flask run

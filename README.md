Kullanılan kütüphaneleri bilgisayarına indirmek için aşağıdaki komutu cmd ekranına ya da linux terminaline yaz 
ve çalıştır.

pip install -r requirements.txt

Bu işlemi yaptıktan sonra kütüphaneler yüklenmiş olacaktır. Olası kütüphane hataları bilgisayarınızdan kaynaklı
olacaktır.


Önerim virtualenv kurarak dosyaları çalıştırmanızdır.

Windows işletim sistemi için virtualenv kurulumu :
cmd ekranında proje dizinini açınız
python get-pip.py
pip install virtualenv
virtualenv -p python3 venv
venv\Scripts\activate
pip install -r requirements.txt
Uygulamayı kapattıktan sonra terminalde venv\Scripts\deactivate yazın.
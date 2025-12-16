# 📋 Python Görev Yönetim Uygulaması (To-Do List)

Bu proje, Python programlama dili kullanılarak geliştirilmiş, komut satırı üzerinden çalışan interaktif bir görev yönetim uygulamasıdır. Kullanıcının görevlerini kaybetmemesi için **Dosya İşlemleri (File Handling)** kullanılarak veriler kalıcı hale getirilmiştir.

## 🚀 Projenin Amacı
Python öğrenme sürecimde; fonksiyonlar, döngüler, hata yakalama (try-except) ve dosya okuma/yazma işlemlerini pekiştirmek amacıyla geliştirilmiştir.

## 🛠️ Özellikler

Bu uygulama temel **CRUD** (Oluştur, Oku, Güncelle, Sil) prensiplerini içerir:

* **Görev Ekleme:** Kullanıcıdan alınan veriyi listeye ekler.
* **Görev Listeleme:** Mevcut görevleri numaralandırılmış şekilde gösterir.
* **Görev Güncelleme:** Var olan bir görevi düzenleme imkanı sunar.
* **Görev Silme:** Tamamlanan veya iptal edilen görevleri listeden kaldırır.
* **Veri Kalıcılığı:** Program kapansa bile veriler `gorev_kaydi.txt` dosyasında saklanır, açıldığında tekrar yüklenir.
* **Hata Yönetimi:** Kullanıcının geçersiz sayı girmesi veya boş veri girmesi gibi durumlarda programın çökmesini engeller.

## 💻 Kullanılan Teknolojiler

* **Dil:** Python 3
* **Kütüphaneler:** `os` (Dosya kontrolü için)
* **Yapı:** Jupyter Notebook (.ipynb)

## ▶️ Nasıl Çalıştırılır?

1.  Bu repoyu bilgisayarınıza klonlayın veya `.ipynb` dosyasını indirin.
2.  Bilgisayarınızda Python yüklü olduğundan emin olun.
3.  Projeyi bir Jupyter Notebook ortamında (Google Colab, JupyterLab veya VS Code) açın.
4.  Kod hücresini çalıştırın ve menüdeki yönergeleri takip edin.

---
**Geliştirici Notu:** Bu proje, Management Information Systems (YBS) lisans eğitimim ve veri bilimi yolculuğumun bir parçası olarak hazırlanmıştır.

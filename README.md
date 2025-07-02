
# 📂 Dosya Şifreleme / Deşifreleme Uygulaması

Bu proje C# Windows Forms kullanılarak geliştirilmis basit bir *dosya şifreleme ve deşifreleme uygulamasıdır*.Uygulamada kullanıcının belirlediği bir anahtar ile seçilen dosyanın içeriği XOR  işlemi kullanılarak şifrelenir veya deşifre edilir.

Bu proje, sifreleme mantığını anlamak ve Windows Forms pratiği yapmak amacıyla hazırlanmıştır.

---

##  Özellikler

✅ Seçilen dosyanın içeriğini **XOR yöntemi ile şifreleme*
✅ Aynı anahtar ile dosyayı tekrar açıp deşifre etme
✅ Basit ve anlaşılır arayüz  
✅ C# dilinde temel dosya okuma/yazma ve dizilerle çalışma pratiğini sağlar.

---

##  Kullandığım Araçlar

- C# (.NET Framework)
- Windows Forms (WinForms)
- Visual Studio

--

## 🖥️ Arayüz

Arayüzde:
- *Dosya Seç:* Dosyayı seçmek için buton
- *Şifrele:* Seçilen dosyayı girilen anahtar ile şifreler
- *Deşifrele:* Şifrelenmiş dosyayı girilen anahtar ile açar
- *Dosya Yolu:* Dosya yolunun görüntülendiği TextBox"tır.
- *Anahtar:* Kullanıcı tarafından girilen şifreleme/deşifreleme anahtarı için TextBox
- İlgili label’lar

--

##  Çalışma Mantığı

- *XOR algoritması*, dosya içeriğindeki her byte'ı anahtarın byte'ları ile sırayla XOR’lar.
- Şifreleme ve deşifreleme işlemi aynıdır ve aynı anahtar kullanıldığında dosya eski haline döner.
- Kullanıcıdan bir password ister ve dosyayı bununla şifreler ve başka bir buton ile deşifreleyip dosyayı kullanıma açar.

---


##  Kullanım

1️⃣ `Dosya Seç` butonuna basarak şifrelemek/deşifrelemek istediğiniz dosyayı seçin.  
2️⃣ `Anahtar` alanına bir şıfreleme anahtarı girin (örneğin: `abc123`)..
3️⃣ `Şifrele` butonuna basarak dosyanın içeriğini şifreleyin.  
4️⃣ Aynı dosyayı tekrar seçip aynı anahtar ile `deşifrele` butonuna basarak dosyanın eski haline dönmesini sağlayın.

---

## ⚠️ Uyarılar

- Şifreleme işlemi **dosya üzerinde direkt değişiklik yapar bu sebepten yedek almak önerilir.**
- Şifreleme sırasında girilen anahtar unutulmamalıdır, aksi takdirde dosya içeriği anlamsız kalacaktır.

---

## 📸 Ekran Görüntüleri

**projenin ekran görüntülerine github dosyasında ayrıca mevcuttur..

---

## hakkımda

📌 **Ad Soyad:  Yusuf Köse 
📌 **Üniversite: Ostim Teknik Üniversitesi
📌 **Bölüm: Yazılım Mühendisliği(türkçe)

--

saygılarımla..

--

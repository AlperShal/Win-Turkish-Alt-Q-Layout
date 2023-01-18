# Windows İçin Türkçe Alt-Q Desteği

## Hakkında

Türkçe Alt-Q, [@nilgun](https://github.com/nilgun) tarafindan Linux'a eklenmiş ve MacOS işletim sisteminde de bulunan, İngilizce klavye düzenlerinde (English US) Türkçe karakterlerin kullanılmasına olanak sağlayan bir klavye düzenidir. Daha önce [@f](https://github.com/f) tarafından Windows'a [uyarlanmıştır](https://github.com/f/win-turkish-us-layout) ve şimdi benim tarafımdan güncellenmektedir.

Bu proje oluşturulurken [@nilgun](https://github.com/nilgun)'ün Linux'a eklediği [Türkçe Alt-Q klavye düzeni](https://cgit.freedesktop.org/xkeyboard-config/tree/symbols/tr) referans alınmıştır ve üzerine eklemeler yapılmıştır.

## Özellikler
- İngilizce klavyelerde bulunmayan Türkçe karakterleri (ı,İ,ç,Ç,ş,Ş,ö,Ö,ü,Ü,ğ,Ğ) destekler.
- Türk Lirası işaretini (₺) destekler.
- Beta işaretini (β) destekler.
- Windows 10 ve 11'de çalışır. Önceki sürümlerde de çalışması beklenir.

## Kurulum
### Hazır Dosyalar
- 'Releases' kısmından düzenin son sürümünu indirebilir ve cihazınıza uygun .msi kurulum dosyasını ya da doğrudan .exe kurulum dosyasını çalıştırarak `Turkish Alt-Q` düzenini Windows bilgisayarınıza ekleyebilirsiniz. (Bu kurulum dosyaları Microsoft Keyboard Layout Creator ile oluşturulmuştur ve üzerlerinde benim tarafımdan herhangi bir değişiklik yapılmamıştır. Kendi yazdığım kurulum dosyaları değillerdir.)
### Kendiniz Oluşturmanız İçin
- [Turkish-Alt-Q.klc](https://github.com/AlperShal/Win-Turkish-Alt-Q-Layout/blob/main/Turkish-Alt-Q.klc) dosyasını bilgisayarınıza kaydedin.
- [Microsoft Keyboard Layout Creator (MKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134)'ı indirin ve kurun.
- MKLC'ı açın ve File > Load Source File butonuna tıklayın.
- Açılan pencereden bilgisayarınıza kaydettiğiniz `Turkish-Alt-Q.klc` dosyasını seçin.
- Project > Build DLL and Setup Package seçeneğini seçin.
- Çıkan uyarıya hayır deyin ve ikinci uyarıya evet deyin. (İkinci uyarı gelmezse `C:\Users\KullaniciAdi\Documents\turkish-` dosyasına gidin.)
- Açılan pencereden cihazınıza uygun .msi kurulum dosyasını ya da doğrudan .exe kurulum dosyasını çalıştırın. Düzen bilgisayarınıza kurulmuş olacaktır.

## Tuş Haritası
- AltGr+i => ı
- AltGr+Shift+i => İ
- AltGr+c => ç
- AltGr+Shift+c => Ç
- AltGr+s => ş
- AltGr+Shift+s => Ş
- AltGr+o => ö
- AltGr+Shift+o => Ö
- AltGr+u => ü
- AltGr+Shift+u => Ü
- AltGr+g => ğ
- AltGr+Shift+g => Ğ
---
- AltGr+t/AltGr+Shift+t => ₺
- AltGr+b/AltGr+Shift+b => β
- \ => <
- Shift+\ => >
- AltGr+\ => |
- AltGr+Shift+\ => ¦

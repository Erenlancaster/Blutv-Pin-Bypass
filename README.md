# <img src="blutv.png" width="45" align="left"> Blutv-Bypass
BluTV, 2015 yılında Doğan Holding çatısı altında kurulan, gerçek zamanlı veri akışı ve seç-izle aracılığıyla internet üzerinden hizmet veren bir medya sağlayıcısıdır.

## TURKISH
Kullanıcının kullandığı pini bilmeden "Response manipulation" taktiğiyle server-side olan cevabı client-side olarak editleyerek 2-factor'u geçtiğim bir güvenlik açığı.

Yapmanız Gerekenler
- Burp'u indirin https://portswigger.net/burp
- Gifteki adımları takip edin ve bu kodu değiştirdiğiniz koda yapıştırın "{"verified":true,"_status":200,"_status_text":"OK","status":200}"
- Artık hesaba erişebilirsiniz
  
BluTV ile iletişime geçtim fakat herhangi bir dönüş alamadım eğer BluTV'de çalışıyorsanız github sayfamdaki mailden ulaşabilirsiniz.

## ENGLISH
It's a vulnerability where I bypass the 2-factor by editing the server-side response as client-side with the "Response manipulation" tactic, without knowing the user's pin.

What you need to do
- Download Burp https://portswigger.net/burp
- Follow the steps in the gift and paste this code into the code you changed "{"verified":true,"_status":200,"_status_text":"OK","status":200}"
- You can now access the account

![blutv](https://github.com/Erenlancaster/Blutv-Bypass/assets/50498704/af070665-4381-4531-bed6-2d71f71833e3)

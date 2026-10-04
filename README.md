# chefanane-davet

Chefanane aile davet bağlantılarının (`https://davet.chefanane.com/katil#<kod>`) sayfası ve Android App Links doğrulama dosyası. GitHub Pages ile yayınlanır.

- Yalnızca herkese açık içerik: `/.well-known/assetlinks.json` (paket adı + imza sertifikası parmak izi) ve `/katil/` sayfası.
- Kod, kullanıcı verisi, secret, harici script / font / analitik **yoktur**.
- Davet kodu adresin `#` sonrasındadır; sunucuya gönderilmez, sayfa onu hiçbir yere göndermez ve saklamaz.
- Uygulama kodu ayrı ve private bir repodadır.

`assetlinks.json` şu an yalnızca **Staging** imza sertifikasını içerir; Production / Google Play imzası yayın öncesinde eklenir.

# claudetransfer-site

Claude Transfer'in tanıtım sayfası, gizlilik politikası ve hizmet şartları. Google'ın OAuth onay ekranı bu sayfaları ister.

Yayın adresi: https://mikrothings.github.io/claudetransfer-site/

Sayfalar düz HTML'dir, derleme adımı yoktur. `main` dalına yapılan her push birkaç dakika içinde yayına çıkar.

Yerelde bakmak için bu klasörde:

```bash
python -m http.server 8765
```

Sonra tarayıcıda http://localhost:8765 adresini açın.

Aracın kendisi private [mikrothings/claude-transfer](https://github.com/mikrothings/claude-transfer) reposundadır. Gizlilik politikasındaki iddialar (yalnız `drive.file` izni, anahtarın DPAPI ile yerelde saklanması, sunucu olmaması) oradaki koda dayanır; kod değişirse bu sayfaları da güncelleyin.

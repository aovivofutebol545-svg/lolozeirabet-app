LolozeirabetApp (Android + WebView)
================================

URL do site: https://lolozeirabet.shop/
Pacote: shop.lolozeirabet.app

Como gerar o APK (no Windows):
1) Instale Android Studio.
2) Abra este projeto (pasta "LolozeirabetApp") no Android Studio.
3) Espere o "Gradle Sync" terminar.
   - Se reclamar do gradle-wrapper.jar, use:
     Tools > Gradle > "Wrapper" (ou crie um wrapper: Gradle > Tasks > build setup > wrapper)
4) Build > Generate Signed Bundle / APK...
   - Selecione APK
   - Crie uma "Key store" (uma vez só) e guarde a senha.
   - Build Type: release
5) O APK vai aparecer em: app/build/outputs/apk/release/

Depois:
- Suba o arquivo .apk para o seu CloudPanel em /public/app/
- Link final: https://SEUSITE.com/app/lolozeirabet.apk
- No seu painel (campo "Link do App" / link_app) cole esse link e salve.

Observação sobre iOS:
- Para gerar IPA (iPhone) precisa de um Mac com Xcode.
- Se você quiser, depois posso te passar o passo a passo com Capacitor para iOS.

# NOVA BOOST

Projeto inicial de aplicativo Android baseado em HTML, empacotado com Capacitor.

## Como usar no GitHub
1. Crie um repositório e envie todos os arquivos desta pasta.
2. No GitHub, abra **Actions**.
3. Escolha **Build NOVA BOOST APK** e clique em **Run workflow** (ou envie um commit para `main`).
4. Quando terminar, abra a execução e baixe o artifact `nova-boost-debug-apk`.
5. Dentro do ZIP do artifact estará `app-debug.apk`.

## Importante
- O APK gerado é de depuração (debug), adequado para instalar e testar.
- Este painel HTML não consegue ler o FPS real do Minecraft nem a temperatura/uso total de CPU/RAM do Android. Mostra apenas dados acessíveis ao navegador e recomendações.
- Para métricas nativas reais seria necessário implementar código Android nativo e permissões/integrações adicionais.

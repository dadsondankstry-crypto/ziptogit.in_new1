
# Arquivando Chat - APK via GitHub

Projeto pronto pra gerar APK no GitHub Actions.

## Como usar (2 min no celular mesmo):
1. Crie um repositório NOVO no GitHub chamado `arquivando-chat-apk` (pode ser privado)
2. Faça upload de TODOS os arquivos desta pasta (mantenha a estrutura)
3. Vá em Actions > clique em "Build APK - Arquivando Chat" > Run workflow ou faça um push
4. Aguarde 2-3 min > clique no run > baixe o Artifact `Arquivando-Chat-v1.2-APK`
5. Instale no Android

O app roda 100% offline porque o index.html já está dentro do APK em `app/src/main/assets/`.

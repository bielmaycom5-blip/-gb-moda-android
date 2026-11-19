# GB MODA Oficial — Projeto Android

Este projeto cria um aplicativo Android simples que abre a loja GB MODA Oficial em uma tela de aplicativo, usando a logo enviada como ícone.

## Como gerar o APK pelo GitHub

1. Crie um repositório no GitHub com o nome `gb-moda-android`.
2. Envie todos os arquivos e pastas deste projeto para a branch `main`.
3. Abra a aba **Actions** do repositório.
4. Selecione **Build GB MODA APK** e toque em **Run workflow** (ou aguarde o build automático após o envio).
5. Quando terminar, abra a execução concluída e baixe o artefato **GB-MODA-Oficial-APK**.
6. Dentro do ZIP baixado estará `app-debug.apk`, pronto para instalar no Android para testes.

## Observações importantes

- O APK abre a versão web publicada em `https://gb-moda-oficial.vercel.app/`; precisa de internet para carregar a loja.
- O APK gerado pelo fluxo é de teste (debug), não é uma versão assinada para publicação na Play Store.
- Este projeto não guarda senhas nem dados de pagamento. O painel e os dados do site continuam sujeitos às limitações da versão web atual.
- Não coloque senhas, chaves privadas ou dados pessoais neste repositório.

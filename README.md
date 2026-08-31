# Revolt Android - chat.painelrp.app.br

App Android (fork patchado do Stoat/Revolt) configurado para conectar
automaticamente no servidor self-hosted **chat.painelrp.app.br**.

## Baixar o APK

**[Clique aqui para baixar o APK](https://github.com/hqscoltt/revolt-android-painelrp/releases/download/v1.0.0/app-debug.apk)**

Ou, se o link acima não abrir direto pra você: va na aba
**[Releases](https://github.com/hqscoltt/revolt-android-painelrp/releases/tag/v1.0.0)**
deste repositorio e baixe o arquivo `app-debug.apk`.

### Como instalar

1. Baixe o `.apk` pelo link acima direto no celular (ou copie pro celular
   depois de baixar no PC).
2. Abra o arquivo baixado. O Android vai avisar que "apps de fontes
   desconhecidas" estao bloqueados por padrao - toque em **Configuracoes** e
   permita a instalacao para o navegador/app que voce usou pra baixar
   (é normal, esse aviso aparece pra qualquer app que nao vem da Play Store).
3. Instale normalmente e abra - ja vem conectado no `chat.painelrp.app.br`.

## O que foi corrigido em relacao ao app oficial

- Todas as URLs de servidor (API, arquivos, proxy, websocket) apontam para
  `chat.painelrp.app.br` em vez do servidor oficial.
- Adicionado toque-para-tela-cheia na visualizacao de tela/video compartilhado
  durante chamadas de voz.

## Nota

Esta e uma build de desenvolvimento (`debug`), nao assinada com certificado
de release da Play Store - por isso o aviso de "fonte desconhecida" ao
instalar. Notificacoes push em segundo plano nao funcionam nesta build
(usa um `google-services.json` de placeholder).

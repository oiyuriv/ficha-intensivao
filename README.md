# Ficha Intensivão

App de celular da ficha de hipertrofia (02/11/2026 a 30/04/2027): treino do dia de manhã e à noite, registro de carga por série, cronômetro de descanso, dieta da fase e check-ins de medidas.

Funciona sem internet depois da primeira abertura. Os registros ficam salvos no próprio celular.

## Publicar no GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
3. Em um ou dois minutos o app fica em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

## Instalar no celular

- **Android (Chrome):** abra o link, toque no menu ⋮ e em **Instalar app** (ou **Adicionar à tela inicial**).
- **iPhone (Safari):** abra o link, toque em **Compartilhar** e em **Adicionar à Tela de Início**.

## Backup

Os dados ficam só no navegador do celular. Na aba **Medidas**, use **Exportar backup** a cada check-in e guarde o arquivo (Drive, WhatsApp, e-mail). Para trocar de celular ou recuperar os dados, use **Importar backup**.

## Atualizar o app

Depois de alterar `index.html`, aumente a versão em `sw.js` (`ficha-intensivao-v1` → `v2`) para o celular baixar a nova versão.

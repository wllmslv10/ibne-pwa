# Escala de Mídia IBNE — PWA

Protótipo de uma página instalável para acesso rápido ao aplicativo oficial da Escala de Mídia IBNE.

## Estado atual

- Página inicial responsiva em `index.html`.
- Metadados de instalação em `manifest.webmanifest`.
- Ícone vetorial em `icons/icon.svg`.
- Service worker que mantém em cache somente a página e os arquivos estáticos deste protótipo.
- Botão que abre o aplicativo oficial: https://escala-midia-ibne.streamlit.app/

## Limites importantes

Este protótipo é uma **página de acesso instalável**, não uma conversão completa do aplicativo Streamlit. O app oficial continua hospedado separadamente. Login, escalas e notificações continuam sob responsabilidade do aplicativo oficial; este protótipo não armazena credenciais, dados pessoais, escalas ou chaves Firebase.

O service worker não intercepta requisições para outros domínios e não tenta armazenar dados do app oficial.

## Publicação para teste

A implementação está na branch `pwa-setup` e ainda não foi publicada nem integrada ao aplicativo oficial. Antes de publicar, validar os arquivos e configurar o GitHub Pages para essa branch (ou publicar por uma branch de implantação separada). Não copiar segredos nem arquivos de configuração privados para este repositório.
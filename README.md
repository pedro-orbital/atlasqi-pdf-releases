# AtlasQI PDF Releases

Distribuição e atualizações oficiais do AtlasQI PDF.

Este repositório é público propositalmente para que o aplicativo instalado possa consultar atualizações sem armazenar credenciais do GitHub.

## Estrutura

- `channels/beta/latest.json` - canal de homologação e desenvolvimento
- `channels/stable/latest.json` - canal estável
- **GitHub Releases** - local dos pacotes binários de atualização

## Regra de armazenamento

Não versionar instaladores, executáveis ou ZIPs na aba **Code**. Os pacotes distribuíveis devem ser anexados exclusivamente às **GitHub Releases**.

## Segurança

O AtlasQI PDF valida cada pacote por HTTPS e SHA-256 antes de iniciar a atualização.

Código-fonte: repositório privado `pedro-orbital/atlasqi-pdf`.
